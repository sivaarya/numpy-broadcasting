macros = array([
[0.8, 2.9, 3.9],
[52.4, 23.6, 36.5],
[55.2, 31.7, 23.9],
[14.4, 11, 4.9]
])

result = zeros_like(macros)

cal_per_macro = array([3, 3, 8])

for i in range(macros.shape[0]):
	result[i, :] = macros[i, :] * cal_per_macro

result

# ft_printf
![image](https://github.com/fbkeskin/Ft_printf/assets/92950254/b5a1854b-0d6f-4813-97db-71f2c7bbd246)
## Status
Bitirme Tarihi: 11/12/2023. Grade: 100/125.
## Basic Usage
Örneğin, bir ``main.c`` dosyası oluşturun.

```c
// header file'i include et.
#include "ft_printf.h"

int main(void)
{
      // fonksiyonu cagir
      ft_printf("ft_printf testi basarili!");
      return (0);
}
```

``main.c`` dosyasını ft_printf kütüphanesi ile compile edin ve programı çalıştırın:
```bash
gcc -o program main.c libftprintf.a
./program
```
Output şu şekilde olacaktır:
```
ft_printf testi basarili!
```

<table>
    <thead>
        <tr>
            <th>Format Specifier</th>
            <th>Description</th>
        </tr>
	</thead>
        <tr>
            <td align="center">%</td>
            <td>başka bir '%' karakterini takip eder ve %'yi ekrana yazar.</td>
        </tr>
        <tr>
            <td align="center">c</td>
            <td>tek bir karakter yazar.</td>
        </tr>
        <tr>
            <td align="center">s</td>
            <td>bir karakter dizisi yazar.</td>
        </tr>
        <tr>
            <td align="center">p</td>
            <td>pointer argümanı 16'lık tabanda yazar.</td>
        </tr>
        <tr>
            <td align="center">d veya i</td>
            <td>işaretli(signed) tamsayıyı ondalık tabanda yazar.</td>
        </tr>
        <tr>
            <td align="center">u</td>
            <td>işaretsiz(unsigned) tamsayıyı ondalık tabanda yazar.</td>
        </tr>
        <tr>
            <td align="center">x veya X</td>
            <td>işaretsiz(unsigned) tamsayıyı 16'lık tabanda yazar.</td>
        </tr>
    </tbody>
</table>

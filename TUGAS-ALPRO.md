Tugas ALPRO 1 Renata
================
Renata Subekti
2026-09-20

## Cek bilangan ganjil/genap

``` r
ganjil_genap <- function(bilangan) {
  ifelse(bilangan %% 2 == 0, "genap", "ganjil")
}
```

### Contoh penggunaan

``` r
# Cek satu bilangan
ganjil_genap(53)
```

    ## [1] "ganjil"

``` r
ganjil_genap(42)
```

    ## [1] "genap"

``` r
ganjil_genap(8263375)
```

    ## [1] "ganjil"

``` r
# Cek banyak bilangan
input <- c(10,21,32,43,54)
ganjil_genap(input)
```

    ## [1] "genap"  "ganjil" "genap"  "ganjil" "genap"

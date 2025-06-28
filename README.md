# 🧵 ft_printf

**ft_printf** is a custom implementation of the standard C `printf` function.
It aims to replicate the behavior of `printf`, handling various format specifiers, flags, and types — all written from scratch in C.

## ✅ Supported Format Specifiers

| Specifier | Description             |
|----------:|-------------------------|
| `%c`      | Character               |
| `%s`      | String                  |
| `%p`      | Pointer (memory address)|
| `%d` / `%i` | Signed integer        |
| `%u`      | Unsigned integer        |
| `%x` / `%X` | Hexadecimal           |
| `%%`      | Percent sign            |

---

## 🛠 Usage

```c
ft_printf("Hello, %s! You scored %d%%.\n", "student", 100);
```

## 🚀 Getting Started

```bash
git clone git@github.com:iriscodinggit/ft_printf.git
cd ft_printf
make


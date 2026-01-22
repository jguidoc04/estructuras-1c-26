# Introducción a C# (C Sharp)

## ¿Qué es C#?
C# (se pronuncia *C Sharp*) es un lenguaje de programación moderno, orientado a objetos y fuertemente tipado, desarrollado por **Microsoft** como parte de la plataforma **.NET**. Es ampliamente utilizado para crear aplicaciones de escritorio, web, móviles, servicios, videojuegos y sistemas empresariales.

C# combina la potencia de lenguajes como C++ con la simplicidad de Java, ofreciendo un entorno seguro, productivo y robusto.

---

## ¿Para qué se usa C#?
C# es un lenguaje **multiplataforma** y se utiliza en muchos tipos de proyectos:

- 🖥️ Aplicaciones de escritorio (Windows Forms, WPF)
- 🌐 Aplicaciones web (ASP.NET, ASP.NET Core)
- 📱 Aplicaciones móviles (Xamarin, .NET MAUI)
- 🎮 Videojuegos (Unity)
- ⚙️ Servicios y APIs REST
- 🏢 Sistemas empresariales
- ☁️ Aplicaciones en la nube (Azure)

---

## Características principales de C#

- **Orientado a Objetos**: usa clases, objetos, herencia, polimorfismo y encapsulación.
- **Fuertemente tipado**: las variables deben tener un tipo definido.
- **Seguro**: manejo automático de memoria mediante *Garbage Collector*.
- **Multiplataforma**: funciona en Windows, Linux y macOS.
- **Integración con .NET**: acceso a una gran biblioteca estándar.
- **Alto rendimiento**.

---

## Plataforma .NET

C# se ejecuta sobre **.NET**, que proporciona:

- CLR (Common Language Runtime)
- Bibliotecas estándar
- Gestión de memoria
- Manejo de excepciones
- Seguridad

Tipos de .NET:

- **.NET Framework** (Windows)
- **.NET Core** (multiplataforma)
- **.NET** (versión unificada actual)

---

## Primer programa en C#

```csharp
using System;

class Program
{
    static void Main()
    {
        Console.WriteLine("Hola mundo desde C#");
    }
}
```

### Explicación:
- `using System;` importa librerías básicas.
- `class Program` define una clase.
- `Main()` es el punto de inicio del programa.
- `Console.WriteLine()` imprime en pantalla.

---

## Variables y Tipos de Datos

### Tipos primitivos

```csharp
int edad = 30;
double salario = 850.75;
bool activo = true;
char letra = 'A';
string nombre = "Jonathan";
```

| Tipo | Descripción |
|----|----|
| int | Enteros |
| double | Decimales |
| bool | Verdadero/Falso |
| char | Un carácter |
| string | Texto |

---

## Operadores

```csharp
int a = 10;
int b = 5;

int suma = a + b;
int resta = a - b;
int mult = a * b;
int div = a / b;
```

Operadores lógicos:

```csharp
bool resultado = (a > b) && (b > 0);
```

---

## Estructuras de Control

### Condicional if

```csharp
if (edad >= 18)
{
    Console.WriteLine("Mayor de edad");
}
else
{
    Console.WriteLine("Menor de edad");
}
```

### Switch

```csharp
switch (dia)
{
    case 1:
        Console.WriteLine("Lunes");
        break;
    default:
        Console.WriteLine("Otro día");
        break;
}
```

---

## Bucles

### For

```csharp
for (int i = 0; i < 5; i++)
{
    Console.WriteLine(i);
}
```

### While

```csharp
int i = 0;
while (i < 5)
{
    Console.WriteLine(i);
    i++;
}
```

---

## Arreglos (Arrays)

```csharp
int[] numeros = { 1, 2, 3, 4, 5 };

foreach (int n in numeros)
{
    Console.WriteLine(n);
}
```

---

## Clases y Objetos

```csharp
class Persona
{
    public string Nombre;
    public int Edad;

    public void Saludar()
    {
        Console.WriteLine($"Hola, soy {Nombre}");
    }
}
```

Uso:

```csharp
Persona p = new Persona();
p.Nombre = "Ana";
p.Edad = 25;
p.Saludar();
```

---

## Métodos

```csharp
static int Sumar(int a, int b)
{
    return a + b;
}
```

---

## Manejo de Excepciones

```csharp
try
{
    int x = 10 / 0;
}
catch (Exception ex)
{
    Console.WriteLine(ex.Message);
}
```

---

## Colecciones

### List

```csharp
List<string> nombres = new List<string>();
nombres.Add("Ana");
nombres.Add("Luis");
```

### Dictionary

```csharp
Dictionary<int, string> usuarios = new Dictionary<int, string>();
usuarios.Add(1, "Admin");
```

---

## ¿Por qué aprender C#?

- Gran demanda laboral
- Ideal para aplicaciones empresariales
- Lenguaje claro y estructurado
- Excelente documentación
- Compatible con videojuegos (Unity)

## Importar clases en C#


```csharp
using NameSpace.NombreClase;


using Biblioteca.Utilidades;


```


## Como pedir un dato en C#


```csharp

Console.ReadLine()

char dia;
Console.WriteLine("Introduzca el dia de la semana en char");
dia = char.Parse(Console.ReadLine());


```





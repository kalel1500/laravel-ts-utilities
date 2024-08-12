# Release Notes

## [Unreleased](https://github.com/kalel1500/laravel-hexagonal-and-ddd-architecture-utilities/compare/v1.1.0-beta.1...master)

## [v1.1.0-beta.1](https://github.com/kalel1500/laravel-ts-utilities/compare/v1.0.0-beta.4...v1.1.0-beta.1) - 2024-07-18

### Fixed

* Corregido error en el método `addClassEditableOnEditableCells`: ejecutar `editable` si es un método al filtrar las columnas y quitar comprobación `isEditableCell` al añadir la clase, ya que con lo anterior ya basta

### Removed

* Eliminado método `addClassEditableOnReceivedEditableCells`, ya que con la corrección anterior ya no hace falta

## [v1.0.0-beta.4](https://github.com/kalel1500/laravel-ts-utilities/compare/v1.0.0-beta.3...v1.0.0-beta.4) - 2024-07-05

### Changed

* Modificar helper pluck() para añadir la funcionalidad de Laravel

### Removed

* Quitar dependencia del paquete `kalel1500/laravel-hexagonal-and-ddd-architecture-utilities` del README.md

## [v1.0.0-beta.3](https://github.com/kalel1500/laravel-ts-utilities/compare/v1.0.0-beta.2...v1.0.0-beta.3) - 2024-06-19

### Changed

* Dependencias actualizadas
* Modificar rutas `checkService` de websockets y queues de `ajax.shared...` a `hexagonal.ajax...` para utilizar las del paquete `laravel-hexagonal-and-ddd-architecture-utilities`
* Mover nombres rutas `checkService` de websockets y queues a constantes
* !Refactor: reestructuración carpetas proyecto para poder añadir en un futuro código para ejecutar en rutas del paquete `laravel-hexagonal-and-ddd-architecture-utilities`
* README.md actualizado para indicar la dependencia del paquete `laravel-hexagonal-and-ddd-architecture-utilities`

## [v1.0.0-beta.2](https://github.com/kalel1500/laravel-ts-utilities/compare/v1.0.0-beta.1...v1.0.0-beta.2) - 2024-06-14

### Added

* Meter código inicial de la aplicación (imports, onerror, tooltips y notifications)
* Crear `UtilitiesServiceProvider` para poder configurar lo que se ejecuta desde la aplicación
* Añadir variables `VITE_MINIFY` y `VITE_SOURCEMAP` en el archivo `.env` para controlar la minificación y el sourcemap

### Changed

* Excluir carpeta `src/_internal` al compilar los tipos con dts para que no se exporte en las funciones internas

### Removed

* Quitar variable .env VITE_ENV

## v1.0.0-beta.1 - 2024-06-14

Primera versión funcional del paquete
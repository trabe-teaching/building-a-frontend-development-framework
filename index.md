# Building a frontend development framework

--

# Building a frontend development framework
(by combining third party frameworks and libraries)

--

# Trabe

https://trabe.io

David Barral david@trabe.io
Asís García asis@trabe.io

-- trabe-green

# Context

--

# Current framework problems

* Archetype, not framework
* Developer dissatisfaction
* Versioning hell
* Technical debt
* Maintenance hell

## Low adoption rate

--

# Solution

* Real framework
* DX (developer experience)
* Semantic versioning + migration path
* Modern technologies
* A series of refined design principles and smart decision making xD

-- trabe-green

#



--

Provide basic components

Also provide complex components that use the basic ones

--

Explicitness

Convention over configuration

Sane defaults

Extension points

--



Source code as documentation

Refactor early. Refactor often.




# Real world problem driven design

Build a solution for a real world problem
Extract framework from the solution
Avoid synthetic APIs




# Third party libraries

* Proven solutions only, only if "really" needed
* Wrap but do not rewrite
* Beware of the update hell. Adapt when needed
* Bugs and pull requests


# Evolution

* Strict Semantic Versioning
* Changelog and migration instructions


# Testing

* Integration vs Unit
* Snapshot testing




# Third parties

* Integrating tools not meant to work together


# Documentation

* Live examples FTW!
* Avoid duplication


# Source control

Rebase vs merge

bisect, history traversing



# Code reviews


Pull request + code review
Tooling: github, bitbucket, gitlab...
Team code review


# Team

Communication
Getting started
Catch up!



# CI

Codebase health check
Automatic release when version changes
Automatic repo tagging


# Code standard

Standardize a code convention
Enforce with a linter
Use a code formatter

e.g. eslint + prettier


# Transpilation

Use the best tools
Use modern versions
Prevent future technical debt



Filosofia Unix. Piezas pequeñas, etc.

Mundo ideal vs realidad. Enfoque purista vs la expectativa del usuario

Bloating de funcionalidades. Resolver todos los casos mal en lugar de resolver el 90% bien. Introducir soluciones adhoc en el framework que satisface una necesidad al 100% vs introducir genérica al 80% pero que dan solución a nuevas necesidades.

Entornos (prod,dev, windows vs Unix), facilidades de depuración.

Programmer friendly: guardas, mensajes de error explicativos. DX (Developer Xperience). Herramientas de desarrollo custom. Documentación offline.

Monorepo vs multirepo

Probar nuevas tecnologías y descartar. Decidir sobre pros y cons desde un plano práctico. (ej. flowtype)

Scaffolding y aprendizaje by example

Ejemplos ejecutables.

Hacer lo necesario. Minimal surface API. Minimal code. Minimal functionalities. Economizar. API mínima viable.

Políticas de deprecación.

Deprecate early: si sobra es mejor quitarlo cuanto antes (huir del ya está hecho), quitar todo lo que esté soportado de serie o mejor por otros.

Cada cosa que haces es un compromiso de cara al futuro: hay que mantenerlo, mejorarlo, etc.

Controlar el tamaño y número de las dependencias. Forzar dependencias con terceros. Limitaciones del tamaño final del paquete. (front. el bundle. En back. El tamaño de las imagenes Docker).

Priorizar bugfixing.

Proceso de selección de tecnología base. Análisis y prototipado.

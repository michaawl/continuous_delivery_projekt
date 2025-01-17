# TechDemo: Continuous Delivery 

## Checklist
For a detailed list of tasks and goals, refer to the [Checkliste](./CHECKLIST.md). This document serves as a guide to ensure all relevant CD aspects are integrated into this demo.

## Table of Contents
1. [Introduction](#introduction)
1. [Uebungen](#uebungen)
3. [Getting Started](#test2)
   - [Prerequisites](#test21)


## Introduction
This repository serves as a guide for the TechDemo of the Continuous Delivery (CD) course. It focuses on integrating CD principles into an existing software project rather than developing new software from scratch. The aim is to demonstrate automated builds, tests, and deployments in a real-world scenario.

## Repository mit Übungen
https://github.com/michaawl/continuous_delivery_uebungen

## Plugins

 ### JUnit

 ### jacoco
 `mvn clean test jacoco:report`

 Dieser Befehl erzeugt eine Ausgabe in target/site/jacoco/index.html

 ### checkstyle
 `mvn checkstyle:check`

 Dieser Befehl erzeugt eine Ausgabe in target/checkstyle-checker.xml
 
 ### surefire
 `mvn surefire-report:report`

 Dieser Befehl erzeugt eine Ausgabe der Testberichte und speichert sie in target/site/surefire-report.html

## test2

### test21
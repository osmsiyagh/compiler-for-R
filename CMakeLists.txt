cmake_minimum_required(VERSION 3.15)
project(untitled1 C)

set(CMAKE_C_STANDARD 11)

add_executable(untitled1 main.c main.h analyseur_lexical.c analyseur_lexical.h analyseur_syntaxique.c analyseur_syntaxique.h gestionnaire_des_erreurs.c gestionnaire_des_erreurs.h)
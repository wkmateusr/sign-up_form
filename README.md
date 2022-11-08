# Frontend Mentor - Intro component with sign up form

![Design preview for the Intro component with sign up form coding challenge](./design/desktop-preview.jpg)

Demo: https://wkmateusr.github.io/sign-up_form/

## INTRO

Este é um desafio Front-end do Frontend Mentor.
*This is a Frontend Mentor Frontend challenge.*

## FINALIDADE - PURPOSE

A finalidade é exibir um formulário responsivo com as seguintes características:
-Identificar se o usuário não digitou informações em algum dos campos;
-Identificar se o usuário digitou o email corretamente.
*The purpose is to display a responsive form with the following characteristics:*
*-Identify if the user has not entered information in any of the fields;*
*-Identify if the user has typed the email correctly.*

## INSTALAÇÃO/ COMO UTILIZAR - INSTALLATION / HOW TO USE

Estrutura base em HTML e estilizado em CSS, as fontes foram importadas do googleapis, foram acrescentadas no final do código em CSS estruturas condicionais ao tamanho de exibição na horizontal para adaptar a apresentação. Quanto ao script de execução, foram criadas constantes acerca dos itens do formulário em questão, chamando variáveis em seguida para testar se cada campo estava vazio ou não; especificamente no email, foi acrescentado mais uma condição onde testa se ele segue o padrão de email ou não. As variantes de erros invocam uma função da estrutura do HTML, o 'span', com uma mensagem personalizada de erro abaixo do item, além disso, também é exibido um ícone de erro.
*Basic structure in HTML and styled in CSS, the fonts were imported from googleapis, conditional structures were added at the end of the CSS code to the horizontal display size to adapt the presentation. As for the execution script, constants were created about the items of the form in question, calling variables afterwards to test if each field was empty or not; specifically in email, one more condition was added where it tests if it follows the email pattern or not. Error variants invoke a function of the HTML structure, 'span', with a custom error message below the item, in addition, an error icon is also displayed.*
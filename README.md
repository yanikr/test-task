# React homework template

Этот проект был создан при помощи
[Create React App](https://github.com/facebook/create-react-app). Для знакомства
и настройки дополнительных возможностей
[обратись к документации](https://facebook.github.io/create-react-app/docs/getting-started).

## Создание репозитория по шаблону

Используй этот репозиторий организации GoIT как шаблон для создания репозитория
своего проекта. Для этого нажми на кнопку `«Use this template»` и выбери опцию
`«Create a new repository»`, как показано на изображении.

## How it works?

User can click on button "Follow" and this action will lead to an increment of
the "followers" counter with changing the appearance of the button. If the user
clicks on "Following" button, followers counter will decrement, and the button
will change the appearance to the basic one.

## How this app has been created

For the modest functionality of the app, all the actions with the increment and
decrement of followers counter has been done with the use of React Hooks
useState and useEffect. To keep the counter at the latest position, the state
has been put into localstorage. Appearance of the page has been adjusted with
the use of styled-components library.

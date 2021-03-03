# Артем Горюшкин

## Контакты

[gitHub](https://github.com/gorushkin) | [linkedin](https://www.linkedin.com/in/gorushkin/) | [telegram](http://t.me/artyomgorushkin)

## Немного обо мне

Пару лет назад как-то неожиданно узнал о такой технологии, как MOOCs (Massive Open Online Courses). Работал бухгалтером, поэтому в свободное время изучал там экономику, смотрел лекции ВШЭ.

Потом из рассылки узнал, что там же можно и основы программирования на языке Python изучить. Попробовал - понравилось).

Потом узнал про HTML Academy, где с огоромным интересоом закончил несколько интенсивов, закончил обучение по профессии "Фронтенд-разработчик", откуда узнал о том, что можно создавать приложения на Java Script, создавать интерактивные страницы, которые взаимодействуют с посетителем. Кто-то из сокурсников начал нахваливать Hexlet. Прошел обучение и устрился верстальщиком, потом стал frontend разработчиком. Люблю и хочу учиться, нравится узнавать новое и оттачивать навыки в старом. Поэтому решил изучить и node js. В настоящее время изучаю бэкенд на node js - Express JS, Fastify, MySQL

В настоящее время работаю frontend разработчиком - пилю интерфейсы.

## Примеры кода

```javascript
    .get(
      '/tasks/:id/edit',
      { name: 'taskEdit', preValidation: app.authenticate },
      async (req, reply) => {
        const [task, users, statuses, labels] = await Promise.all([
          app.objection.models.task.query().findById(req.params.id).withGraphJoined('labels'),
          app.objection.models.user.query(),
          app.objection.models.status.query(),
          app.objection.models.label.query(),
        ]);
        reply.render('tasks/edit', {
          task,
          users,
          statuses,
          labels,
        });
        return reply;
      },
    )
```

## Примеры работ
### Чат

* [репозиторий](https://github.com/gorushkin/frontend-project-lvl1)
* [рабочая версия](https://polar-thicket-77600.herokuapp.com/)

### Task Manager

* [репозиторий](https://github.com/gorushkin/taskmanager)
* [рабочая версия](https://taskmanager-gav.herokuapp.com/)

### Veles

* [репозиторий](https://github.com/gorushkin/veles)
* [рабочая версия](https://gorushkin.github.io/veles/)

## Технологии, которые я знаю и использую

* HTML5, CSS3, SCSS
* БЭМ
* JavaScript(ES6+)
* React, React (hooks);
* Redux, Redux Toolkit, Forms;
* Express
* Fastify
* TDD, JEST
* Git, Github, Github Action;
* Babel, Webpack, Gulp;
* Node.JS
* Figma, Photoshop, Avocode

## Отпыт работы

* 2019-2020 Верстальщик - кроссбраузерная, адаптивная верстка
* 2020 - настоящее время - frontend разрабтчик. Занимаюсь интерфейсами

## Образование

* HTML Academy - 2018-2019
* Hexlet 2019-2020 - Frontend разработчик
* Hexlet 2020-2021 - Backend разработчик

## Уровень английского

Свободное чтение документации. Понимаю речь (не всегда, к сожаление)
---
layout: page
title: Изменение представления и макета
order: 2
locale: ru
---

## Изменение представления

Настройка стиля страниц AMP и их элементов выполняется с использованием стандартных свойств CSS. Вы можете изменить стиль элементов, используя селекторы классов или элементов в таблице стилей `<style amp-custom>`, встроенной в раздел `<head>`:

{% highlight html %}
<style amp-custom>
  /* any custom style goes here */
  body {
    background-color: white;
  }
  amp-img {
    background-color: gray;
    border: 1px solid black;
  }
</style>
{% endhighlight %}

Каждая страница AMP может иметь только одну встроенную таблицу стилей, в которой не разрешается использовать некоторые селекторы. [См. дополнительную информацию о настройке стиля](/docs/guides/responsive/style_pages.html).

## Управление макетом

В разметке AMP используются более строгие правила расположения элементов на странице. Для расположения элементов на обычной странице HTML как правило используются только таблицы CSS. Однако разметка AMP в целях повышения скорости отображения требует указания точных размеров всех элементов с самого начала.

Дополнительная информация о том, как разметка AMP выполняет визуализацию и компоновку страницы, а также о способах изменения макета содержится в разделе [Управление макетом](/docs/guides/responsive/control_layout.html).

{% include button.html title="Перейти к шагу 4" link="/docs/get_started/create/preview_and_validate.ru.html" %}
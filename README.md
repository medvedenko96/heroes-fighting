**Heroes Fighting**

 1. Написать базовый класс `Hero` который принимает параметрами конструктора имя героя и количество жизни (значение по умолчанию 150).
  Класс героя должен содержать методы `shot(otherHero)` и `kick(otherHero)` которые наносят повреждения другому герою (`otherHero`).
   Метод `shot` должен наносить 15 очков повреждений, метод `kick` - 5. Также класс должен иметь метод `getLifeValue()` , возвращающий
   количество жизни героя. Написать дочерний класс `SuperHero`, с усиленными повреждениями. Метод `shot` супер-героя должен наносить 25
   очков повреждений, `kick` - 10.

 2. Создать консольную игру для двух игроков, управление которой идет с клавиатуры, `n` - новая игра (создаются два героя, случайным
 образом определяется тип героя и количество жизни (от 100 до 150), то есть в игре могут быть `hero-hero`, `hero-superhero`,
  `superhero-superhero` с разными количествами жизни). Первый герой играет кнопками `q`, `w`, второй `o`, `p`, (соответственно
  `kick` и `shot`). В консоли должен вестись лог игры, на каждое повреждение выводить строку ` ${Имя героя} ${тип повреждения shot/kick}
   -${количество повреждений} from ${Имя поврежденного героя} rest ${остаток жизни поврежденного героя}`. При достижении 0 жизней каким
   либо из героев, вывести сообщение кто выиграл и сколько жизней у него осталось.
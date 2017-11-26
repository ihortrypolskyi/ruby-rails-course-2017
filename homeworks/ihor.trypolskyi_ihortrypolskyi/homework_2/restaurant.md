#архитектура ресторана

класс Ресторан
  атрибуты: название
            расположение
            время работы


класс Персонал
  атрибуты(общие для субклассов): имя
                                  возраст
                                  пол
                                  усталость

        класс Персонал зала
          методы(общие для субклассов): здоровется с посетителем


                  класс Портье
                    методы: открывает двери
                            закрывает двери

                  класс Гардеробщик
                    методы: берет одежду
                            отдает одежду

                  класс Ресепшионист
                    методы:  проводит посетителя на незанятый столик

                  класс Официант
                    методы: записывает заказ
                            относит заказ на кухню
                            приносит(дринк, первое, второе, десерт)
                            уносит грязную посуду((дринк, первое, второе, десерт))
                            серверует стол(дринк, первое, второе, десерт)
                            приносит чек

                  класс Бармен
                    методы: готовит дринк


        класс Персонал кухни

                  класс Шеф-повар
                    методы: командует начать приготовление блюда (первое, второе, десерт)
                            зовет официанта

                  класс Повар
                    методы: готовит блюда (первое, второе, десерт)

                  класс Мойщик
                    методы: моет посуду



класс Посетитель
  атрибуты: сытость

  методы: бронирует столик
          заходит в ресторан
          снимает пальто
          садится за стол
          делает заказ
          пьет дринк
          ест(первое, второе, десерт)
          оплачивает заказ
          дает чаевые
          одевает пальто
          выходит из ресторана


класс Стол
  атрибуты: номер
            количество мест
            занят?


класс Блюдо
  атрибуты: название
            категория(первое, второе, десерт)
            ингридиенты
            стоимость
            время приготовления
            приготовлено?


класс Заказ
  атрибуты: создан?
            номер
            количество блюд
            сумма заказа
            оплачен?


класс Чаевые
  атрибуты: сумма
            оплачен?


класс Посуда
  атрибуты: чистая?

# tursum-carousel

Карусель, которую я создал ради практики.

Инициализируется запуском функции setCarousel(), единственным аргументом которой передаем объект типа:

{ // указаны значения по умолчанию, кроме id

	id: carouselId, // id элемента, в котором будет карусель
	columns: 1, // количество слайдов на экране
	useArrows: false, // возможность использования стрелок для управления слайдами
	useDrag: false, // возможность пролистывания карусели мышью
	timer: 0, // время автоматического пролистывания. Если 0, то не пролистывает
	transition: 200, // время анимации пролистывания
	cycle: false // зацикливание карусели
}

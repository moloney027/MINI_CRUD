# Вспомогательная библиотека для хранения данных в памяти приложения

Пример её использования:

const storage = new StorageService();
storage.add(); //принимает объект и позволяет добавить его в коллекцию
storage.getById(); //принимает id и возвращает найденный объект или NULL если не найден
stotage.getAll(); //возвращает весь массив объектов
storage.deleteById(); //принимает id и возвращает удаленный объект
storage.updateById(); //принимает id первым параметром и объект-вторым. Обновляет поля объекта новыми значениями
storage.replaceById(); //принимает id и заменяет старый объект - новым
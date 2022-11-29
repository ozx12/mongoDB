db.books.insertMany( [
      { title: "Книга 1", description: "Описание Книги 1", authors: "Авторы Книги 1"  },
      { title: "Книга 2", description: "Описание Книги 2", authors: "Авторы Книги 2"  }      
   ] );


db.books.find({ title: "Книга 1"});


db.books.updateOne({"_id":ObjectId("63854e718ea8a2795fca99a6")}, {$set: {"title": "Новая Книга 1", "authors": "Новые Авторы Книги 1"}});
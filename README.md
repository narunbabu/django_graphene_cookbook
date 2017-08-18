# django_graphene appication
Constructed using http://docs.graphene-python.org/projects/django/en/latest/tutorial-plain/

Graphql to serve as GraphQL REST

Follow the commands given in django commands folder
Go to 
/cookbook/cookbook
Run with command
python ../manage.py runserver

http://127.0.0.1:8000/graphql


query{
  allCategories {
  name
}
}

query {
  allIngredients {
    
    name,id
  }
}

look for ingrediants folder
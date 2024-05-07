# Bootstrap

Este es una descripción de los componentes utilizados para hacer el diseño

## 1. Container

```html
    <div  class="py-2 container text-center">
        <h1>Top values for you</h1>
    </div>
```

## 2. Grid con columnas de 4 responsive

```html
    <section class="container">
        <div class="row justify-content-evenly">
            <div class="text-center col-lg-3 col-md-3 col-sm-6 py-2 ">
                <img src="./images/image1.png" class="img-fluid icon" alt="ícono">
                <h5>Airport pickup</h5>
                <p class="fs-6">Lorem ipsum dolor sit amet consectetur adipisicing elit..</p>
            </div>
            <div class="text-center col-lg-3 col-md-3 col-sm-6 py-2 ">
                <img src="./images/image1.png" class="img-fluid  icon" alt="ícono">
                <h5>Easy booking</h5>
                <p class="fs-6">Lorem ipsum dolor sit amet consectetur adipisicing elit..</p>
            </div>
            <div class="text-center col-lg-3 col-md-3 col-sm-6 py-2 ">
                <img src="./images/image1.png" class="img-fluid  icon" alt="ícono">
                <h5>Best tour guide</h5>
                <p class="fs-6">Lorem ipsum dolor sit amet consectetur adipisicing elit..</p>
            </div>
            <div class="text-center col-lg-3 col-md-3 col-sm-6 py-2 ">
                <img src="./images/image1.png" class="img-fluid  icon" alt="ícono">
                <h5>Lost of promos</h5>
                <p class="fs-6">Lorem ipsum dolor sit amet consectetur adipisicing elit..</p>
            </div>
        </div>
    </section>
```


## 3. Imágenes

```html
    <img src="./images/image1.png" class="img-fluid  icon" alt="ícono">
```

## 4. Cards

```html
            <div class="card col-lg-3 col-md-6 col-sm-6 py-2" >
                <img src="./images/image2.jpeg" class="card-img img-fluid" alt="Nature">
                  <div class="d-flex justify-content-between align-items-center raiting text-center">
                    <small class="text-muted">5.0 ★</small>
                  </div>
                  <div class="card-body">
                    <h5 class="card-title">Alone with nature</h5>
                    <p class="card-text">$100/person</p>
                  <a href="#" class="card-icon"><i class="fas fa-chevron-right"></i></a>
                </div>
              </div>
```

## 5. Botones

```html
<button type="button" class="btn btn-light">See all</button>
```

## 6. Íconos

```html
<i class="fas fa-chevron-right"></i>
```
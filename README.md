 *{
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      text-decoration: none;
   }
   body{
     height: 100vh;
     width: 100vw;
     background-color: #EFD9FF;
     display: flex;
     align-items: center;
     justify-content: center;
   }
    .product-card{
      height: 400px;
      width: 300px;
      background-color: white;
      border-radius: 1rem;
    }
   .image-container{
     display: flex;
     align-items: center;
     justify-content: center;
      margin: 1.5rem;
   }
    img{
      height:  240px;
      width: 240px;
      border-radius: 1rem;
    }
    .product-info{
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      padding: 1rem;
      position: relative;
    }
    h2{
      margin-bottom: 0.5rem;
      font-size: 1.5rem;
      align-self: self-start;
    }
    p{
      margin-bottom: 1rem;
      align-self: self-start;
      font-size: 2rem;
      font-weight: 1000;
      color: royalblue;
    }
    a{
      align-self: self-end;
        position: absolute;
        margin-top: 1rem;
        font-size: 25px;
    }

*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

#nav-list{
    list-style: none;
    font-size:1rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;

}

.cantainer{
    height: 130vh;
    width: 100vw;
    overflow-x: none;
    background-color: #aecbe7;
    background-image: linear-gradient(62deg, #aecbe7 0%, #E0C3FC 50%, #dfd5d5 100%);

    
    /* display: flex;
    justify-content: space-between;
    align-items: center; */
}
.navbar{
    /* background-color: rgb(211, 117, 16); */
    background-color: #4158D0;
    background-image: linear-gradient(43deg, #4158D0 0%, #C850C0 46%, #ffd270 100%);
    /* padding-bottom: 30px; */
    width: 100vw;
    height: 60px;
    /* align-items: center; */
    display: flex;
    justify-content: center;
    align-items: center;

}


nav{
    width:100%;
}

#nav-logo-name{
    font-size:2rem;
    padding-left: 20px;
    background-image: url(bg-4.gif);
    background-size: cover;
    background-position: center;
    background-clip: text;
    -webkit-background-clip: text;
    color: transparent;
}

#nav-link{
    font-size: 1.6rem;
    padding-right: 60px;
    align-items: center;
    display: flex;
    gap: 30px;
    
}

#nav-link a{
    text-decoration: none;
    /* display: flex; */
    color: black;
}

/* footer{
    align-items: center;
} */
.footer-box{
    background-color: #4158D0;
    background-image: linear-gradient(43deg, #4158D0 0%, #C850C0 46%, #ffd270 100%);
    text-align: center;
    height: 40px ;
    /* display: flex; */
    /* align-items: center; */

}

.footer-box p{
    font-size: 1.5rem;
}

.content-box{
    width: 80%;
    margin: auto;
    /* height: 18rem; */
    /* border: 1px solid black; */
    /* background-color: #000000;
    background-image: linear-gradient(160deg, #000000 0%, #7e6abc 100%); */
    /* background-color: #db70c4; */
    display: flex;
    /* align-items: center; */
    flex-direction:column;
    gap: 120px;
    padding: 5rem;
    border-radius: 15px;
    background: #db70c4;
    box-shadow:  1px 1px 20px #391f33;
            /* -10px -10px 20px #ffb3ff; */
            background-image: linear-gradient( 135deg, #F05F57 10%, #6c1281 100%);

}

.item{
    display: flex;
    justify-content: space-around;
}

.item .right-box img{
    width: 300px;
    height: 300px;
    border-radius: 20px;
    transition: all ease 1s;
}

.right-box{
    overflow: hidden;
    position: relative;
    transition: all 0.3s linear 0s;
    border-radius: 21px;
/* background: #949393;
box-shadow:  3px 3px 20px #a09f9f,
            -3px -3px 20px #908d8d; */
}

.right-box:hover{
    scale: 1.1;

}

.item-2 .right-box img{
    border-radius: 20px;
}

.ingbox{
    font-size: 1.3rem;

}

.recipebox{
    font-size: 1.1rem;
}

.left-box h2{
    font-size: 2rem;
    color: #055584;
/* background-image: linear-gradient(160deg, #055584 0%, #3b534f 100%); */
    

}

.ing h2{
    /* color: #0093E9; */
    color: #dfd5cf;
/* background-image: linear-gradient(160deg, #0093E9 0%, #80D0C7 100%); */
}

.recipe h2{
    color: #dfd5cf;
}

.ingbox{
    padding-bottom: 20px;

}

.right-box .overlay{
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    background-color: rgba(36, 34, 34, 0.575);
    border-radius: 20px;
    display: flex;
    align-items: center;
    justify-content: center;
    opacity: 0;
    transition: all 0.3s linear 0s;
}

.right-box .overlay span{
    color: white;
    font-size: 1.2rem;
}

.right-box:hover .overlay {
    opacity: 1;
}

body {
  background: #000;
  overflow: hidden;
  margin: 0;
  background-color: #ff8787 !important;
}

h3 {
  position: absolute;
	top: 5%;
	left: 50%;
	transform: translate(-50%, -50%);
	color: rgb(245, 200, 200);
	font-family: "Raleway", sans-serif;
	font-size: 35pt;
}
h3::before {
  content: attr(data-text);
  position: absolute;
  z-index: -1;
  color: rgba(0, 0, 0, 0.2);
  text-shadow: 4px 4px 10px rgba(0, 0, 0, 0.3); 
  transform: rotateX(10deg) rotateY(10deg);
}

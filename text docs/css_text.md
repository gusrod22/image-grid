img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.main-content {
  font-family: "Nunito Sans", sans-serif;
  color: white;
  margin-top: 50px;
}
.user-card {
  background-color: #232b2d;
  border-bottom-right-radius: 10px;
  border-bottom-left-radius: 10px;
  /* border-radius: 10px; */
}
.user-card .top-user-card {
  display: flex;
}
.top-user-card {
  height: 200px;
}
.top-left-user-card-container {
  width: 70%;
  box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.5);
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;
}
.top-right-user-card-container {
  width: 50%;
  position: relative;
}
.pinned-image-container {
  position: absolute;
  width: 68%;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  max-width: 100%;
  max-height: 100%;
}

.pinned-image-container img {
  width: auto;
  height: auto;
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
  border-radius: 15px;
}
.pfp-container {
  position: relative;
  height: 100%;
  border-radius: 0 10px 10px 0;
}
.pfp-container img {
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;
  display: block;
  max-width: 100%;
}
.name {
  font-weight: 600;
  position: absolute;
  bottom: 5px;
  left: 5px;
  color: white;
  text-transform: uppercase;
}
.bottom-user-card {
  display: flex;
  padding: .5rem;
}
.bottom-left-user-card-container{
  text-align: center;
  width: 70%;
}
.bottom-right-user-card-container{
  display: flex;
  justify-content: center;
  align-items: center;
}
button {
  background-color: #253f37;
  color: white;
  border: none;
  width: 120px;
  height: 40px;
  border-radius: 20px;
}

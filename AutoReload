let reloadTimerId = 0;
document.body.addEventListener("mousemove", (event) => {
const x = event.clientX;
const y = event.clientY;
const coor = "Coordinates: (" + x + "," + y + ")";


if(reloadTimerId)
  clearTimeout(reloadTimerId);
  
reloadTimerId = setTimeout(() => {
location.reload();
}, 60000);
});

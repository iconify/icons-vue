<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="whhsmd9xt"/><path class="ichzmofiq"/><path class="r-718rbao"/><path class="cs-zgebln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:thinky-games" /></template>
<style>
.cs-zgebln {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.115 19.474c-2.517-1.034-6.963-4.76-6.532-6.877c.41-2.02 5.7-3.724 5.7-3.724M20.458 35.5c-.505 2.551.392 7.233.392 7.233c-1.542.337-4.432-.112-4.432-.112m13.012-6.897c.505 2.552-.393 7.234-.393 7.234c1.543.336 4.583.332 4.583.332");
}

.ichzmofiq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.852 10.752c-2.855-.204-5.797.466-6.525 3.787c-.728 3.233 1.631 5.36 3.961 6.117c6.73 2.126 9.963-.087 10.429-2.738c.932-5.477-5.214-6.962-7.865-7.166");
}

.r-718rbao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.646 13.123c-.256.177-.611.749-.138 1.38c.256.334.965.827 1.596.393c.571-.374.532-.926.217-1.379c-.276-.394-.966-.847-1.675-.394m-10.4-6.77c-1.071-1.598-2.134-2.386-3.73-.7s.227 3.966.227 3.966");
}

.whhsmd9xt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.707 35.512c-1.66.066-5.883.14-6.991.146c-1.47.007-3.787-.224-4.515-.262c-.904-.048-1.835-.263-2.71-.554a4.73 4.73 0 0 1-2.475-2.097c-.525-.816-.874-2.71-.962-3.641c-.145-2.71-.186-5.42-.029-8.128c.048-.816.145-2.447.204-3.262c.179-2.449.495-5.36 1.078-6.962c.262-.728.64-1.398 1.165-1.952c.641-.64 1.777-.728 2.68-.845c1.31-.145 4.836-.262 6.467-.262c1.66.03 4.952.175 6.583.379c2.593.32 3.437 1.427 4.224 2.33c.64.7 1.223 2.593 1.427 3.525c.496 2.097.554 6.467.583 8.622c.029 1.806 0 5.419-.175 7.166c-.233 1.69-.175 2.68-1.748 4.428c-.64.7-2.65 1.049-3.583 1.224c-.35.058-.756.127-1.223.145");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="upot3l8fk"/><path class="h1u6tlbhc"/><path class="btz_pgyhr"/><path class="wbauw86vf"/><path class="puvzxybrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yummly" /></template>
<style>
.btz_pgyhr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 13.896c.76-1.425 5.465-2.272 4.695.967l-2.386 8.17c-.366 2.172 1.458 4.49 7.69.547l-.835 6.656c-2.725 11.92-11.406 1.49-2.225-1.178c3.233-1.09 15.582 2.063 21.012 2.602c3.987.3 5.764.043 9.049-1.983");
}

.h1u6tlbhc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.273 27.515c-.719-.472.365-4.74.585-7.093c.007-1.393-1.45-3.012-5.558.118c-.397 2.262-1.375 7.625-.804 6.786");
}

.puvzxybrp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.11 24.87c-.096.822-.686 2.95-.11 2.407");
}

.upot3l8fk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.215 21.038c.097-.822.687-2.951.11-2.407m9.829 8.968c-.718-.472.365-4.74.585-7.093c.007-1.394-.403-3.5-4.512-.37");
}

.wbauw86vf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.213 12.282c.55-.44.559.527.528.965L15.48 23.74m5.609-5.583c.718.472-.365 4.74-.585 7.093c-.008 1.393 1.45 3.012 5.557-.118c.397-2.262 1.375-7.625.804-6.786");
}

</style>

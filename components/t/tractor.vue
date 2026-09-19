<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="c1pljv3gv"/><circle class="i7i3nobeb"/><path class="hn1fy2fbd"/><path class="xwjqy1bxe"/><circle class="mp35a5gbp"/><circle class="v8cr412fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tractor" /></template>
<style>
.c1pljv3gv {
  cx: 35.319px;
  cy: 29.628px;
  r: 8.134px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hn1fy2fbd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.414 26.65l-.815-3.176c-.841-3.271 3.613-4.219 15.687-4.219l.635-5.966h-.578a.64.64 0 0 1-.64-.67l.067-1.504a.64.64 0 0 1 .627-.612l13.447-.264a1.45 1.45 0 0 1 1.475 1.327l.537 6.291s3.572.198 4.475 1.585c.395.607.684 1.57.684 1.57");
}

.i7i3nobeb {
  cx: 10.589px;
  cy: 32.029px;
  r: 5.338px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mp35a5gbp {
  cx: 35.319px;
  cy: 29.628px;
  r: 3.305px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v8cr412fj {
  cx: 10.589px;
  cy: 32.029px;
  r: 2.511px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xwjqy1bxe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.313 32.029c-.183-.771-.32-1.575-.32-2.401c0-5.703 4.623-10.327 10.327-10.327c2.104 0 4.062.63 5.695 1.711c.95.63 1.79 1.412 2.485 2.313M5.414 26.65a7.465 7.465 0 0 1 12.64 5.379m0 0h7.259m-2.125-7.791h-.272a.657.657 0 0 1-.653-.722l1.011-10.198a.657.657 0 0 1 .654-.592h7.745c.363 0 .657.294.657.657v3.189a.654.654 0 0 1-.487.627a12.93 12.93 0 0 0-8.074 6.672a.65.65 0 0 1-.582.367M4.672 21.93c2.946-.399 3.837-.26 3.837-.26c-.21.98-1.046 1.978-3.553 3.195");
}

</style>

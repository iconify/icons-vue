<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-44.99 27.881 35.257)" class="p5qu8dfod"/><ellipse transform="rotate(-44.99 24.792 32.936)" class="vgyjl5tnx"/><ellipse transform="rotate(-44.99 21.703 30.827)" class="i8e6c03tv"/><ellipse transform="rotate(-44.99 18.614 28.486)" class="i5rh9xbtu"/><path class="eon8qrlaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microcoil-calculator" /></template>
<style>
.eon8qrlaw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.214 28.885c-3.03 3.03-6.66 4.493-8.176 2.978s-.287-5.199 2.743-8.228a13.8 13.8 0 0 1 3.453-2.557m.104-.052c1.498-.79 2.733-1.695 2.975-3.613L19.01 4.5m19.6 8.704c-.51 6.68-1.901 17.083-1.532 20.037c.234 1.812-1.031 4.534-3.365 6.867c-3.03 3.03-6.715 4.258-8.23 2.743s-.308-4.863 2.722-7.893");
}

.i5rh9xbtu {
  cx: 18.614px;
  cy: 28.486px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.759px;
  ry: 3.879px;
}

.i8e6c03tv {
  cx: 21.703px;
  cy: 30.827px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.759px;
  ry: 3.879px;
}

.p5qu8dfod {
  cx: 27.881px;
  cy: 35.257px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.759px;
  ry: 3.879px;
}

.vgyjl5tnx {
  cx: 24.792px;
  cy: 32.936px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.759px;
  ry: 3.879px;
}

</style>

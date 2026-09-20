<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="olk-khbjb"/><path class="hdpzeebeb"/><path class="b_aseob1v"/><path class="onz3kab9l"/><path class="x1ie-hm9t"/><circle class="wsc9q2a4k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xprivacylua" /></template>
<style>
.b_aseob1v {
  d: path("m33.867 14.588l-1.974 7.927l-7.938.022");
}

.hdpzeebeb {
  d: path("m8.447 20.749l6.1-6.105l1.437 7.913l8.029-.03l.065-11.005M19.974 37.72l4.164-4.163l-.228-10.848");
}

.olk-khbjb {
  cx: 31.761px;
  cy: 31.578px;
  r: 2.56px;
}

.onz3kab9l {
  d: path("M33.238 37.597a17 17 0 0 1-9.683 3.034c-9.519 0-17.235-7.864-17.235-17.566c0-9.7 7.716-17.565 17.235-17.565S40.79 13.364 40.79 23.065a17.78 17.78 0 0 1-3.687 10.858");
}

.wsc9q2a4k {
  cx: 39.092px;
  cy: 39.911px;
  r: 2.589px;
}

.x1ie-hm9t {
  d: path("M24.135 11.471a14 14 0 0 0 7.533 3.052c.73.063 1.464.067 2.191.012");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mrjyxykws"/><circle class="vc8usy25a"/><circle class="n5li2zivg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sainsburys-groceries" /></template>
<style>
.mrjyxykws {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.175 5.5l7.674 27.184a2.125 2.125 0 0 0 2.052 1.577h16.354c.962 0 1.804-.647 2.053-1.577l3.206-10.217c1.227-4.58-1.251-7.835-6.04-7.835h-22.72");
}

.n5li2zivg {
  cx: 32.968px;
  cy: 39.667px;
  r: 2.833px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vc8usy25a {
  cx: 20.351px;
  cy: 39.667px;
  r: 2.833px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

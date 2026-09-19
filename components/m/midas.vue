<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="yy3q-jb_s"/><ellipse class="ib2qypbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:midas" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ib2qypbjl {
  cx: 13.569px;
  cy: 29.226px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.069px;
  ry: 2.091px;
}

.yy3q-jb_s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.365 30.991c.434-.207.79-.465.79-.574s-1.361-2.898-3.025-6.199c-3.22-6.392-3.807-7.211-5.371-7.505c-.883-.165-2.534.266-2.703.706c-.133.346 5.765 12.112 6.415 12.8c1.057 1.114 2.554 1.41 3.894.772m10.345 0c.435-.207.79-.465.79-.574s-1.36-2.898-3.024-6.199c-3.221-6.392-3.807-7.211-5.372-7.505c-.883-.165-2.534.266-2.703.706c-.133.346 5.765 12.112 6.416 12.8c1.057 1.114 2.554 1.41 3.893.772");
}

</style>

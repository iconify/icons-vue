<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ruvyh9mnl"/><path class="rwin9ss5l"/><rect class="fg3z7js4a"/><rect class="il9qhfb8l"/><rect class="o19qbh6ft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:photo-gallery" /></template>
<style>
.fg3z7js4a {
  width: 4.5px;
  height: 3.5px;
  x: 2.75px;
  y: 17.75px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.il9qhfb8l {
  width: 4.5px;
  height: 3.5px;
  x: 9.75px;
  y: 17.75px;
  rx: 1px;
}

.o19qbh6ft {
  width: 4.5px;
  height: 3.5px;
  x: 16.75px;
  y: 17.75px;
  rx: 1px;
}

.ruvyh9mnl {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

.rwin9ss5l {
  d: path("m2.75 12.75l4.5-4.5l4.5 4.5m-1.5-1.5l2-2l4.5 4.5");
}

</style>

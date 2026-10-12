<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x79d704_a"/><path class="v9vdzgxxa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:soil-layers" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v9vdzgxxa {
  d: path("M2.75 13.25c2.25 0 2.25-1 4.5-1s2.25 1 4.75 1s2.25-1 4.5-1s2.5 1 4.75 1m-18.5 4c2.25 0 2.25-1 4.5-1s2.25 1 4.75 1s2.25-1 4.5-1s2.5 1 4.75 1M12 9.5v-4m0 .5c0-2 1.25-3.25 3.5-3.25c0 2-1.25 3.25-3.5 3.25m0 1c0-1.75-1.1-2.75-3-2.75C9 6 10.1 7 12 7");
}

.x79d704_a {
  width: 18.5px;
  height: 11.75px;
  x: 2.75px;
  y: 9.5px;
  rx: 2px;
}

</style>

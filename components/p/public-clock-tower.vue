<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e-m7gwwzb"/><path class="ygq9ny9jm"/><path class="kmqlzfbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:public-clock-tower" /></template>
<style>
.e-m7gwwzb {
  d: path("M6.5 21.5V8L12 2.5L17.5 8v13.5ZM5 8h14M4.5 21.5h15");
}

.kmqlzfbzn {
  d: path("M12 12.5V14h1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ygq9ny9jm {
  d: path("M8.5 14a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

</style>

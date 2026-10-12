<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="als1xf55j"/><path class="yztocec_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:route-map-sharp" /></template>
<style>
.als1xf55j {
  d: path("m2.75 6.4l.002-.684l.638-.246L8.5 3.5l7 2.5l5.11-1.96l.636-.225l.004.675v13.1l-.002.684l-.638.246l-5.11 1.98l-7-2.5l-5.11 1.96l-.636.225l-.004-.675ZM8.5 3.5V18m7-12v14.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yztocec_x {
  d: path("m5.5 15.25l4-4.25l4 2.75l4.75-5.25");
}

</style>

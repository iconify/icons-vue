<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xf07dvr8m"/><path class="tr_jskylo"/><path class="hxoe7gx5p"/><path class="e0001wg8c"/><path class="y_21nobec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:waterfall-outline-thin" /></template>
<style>
.e0001wg8c {
  d: path("M17 5v12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxoe7gx5p {
  d: path("M12 5v12");
}

.tr_jskylo {
  d: path("M7 5v12");
}

.xf07dvr8m {
  d: path("M2 5h20");
}

.y_21nobec {
  d: path("m3 21 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

</style>

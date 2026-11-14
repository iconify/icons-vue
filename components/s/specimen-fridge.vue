<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f6aqqrbxt"/><path class="hd8b2vurz"/><path class="wmzuyfbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:specimen-fridge" /></template>
<style>
.f6aqqrbxt {
  d: path("M9 2.5h6A3.5 3.5 0 0 1 18.5 6v10.5A3.5 3.5 0 0 1 15 20H9a3.5 3.5 0 0 1-3.5-3.5V6A3.5 3.5 0 0 1 9 2.5m-3.5 6h13M8 4.5v2M8 11v3.5M7.75 20v1.5m8.5-1.5v1.5");
}

.hd8b2vurz {
  d: path("M12.75 11v5.25c0 .85.65 1.5 1.5 1.5s1.5-.65 1.5-1.5V11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wmzuyfbzj {
  fill: currentColor;
  d: path("M12.75 14.25h3v2c0 .85-.65 1.5-1.5 1.5s-1.5-.65-1.5-1.5Z");
}

</style>

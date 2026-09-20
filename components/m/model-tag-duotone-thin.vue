<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="edllzuogn"/><path class="woqkegr2j"/><path class="iaozfqbuj"/><path class="tj2c-nb2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:model-tag-duotone-thin" /></template>
<style>
.edllzuogn {
  fill: currentColor;
  d: path("M14.5 4H17a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V8l4 -4h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iaozfqbuj {
  d: path("M14.5 4H17a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V8l4 -4h2.5");
}

.tj2c-nb2i {
  d: path("M8 8h4l4 4 -4 4H8Z");
}

.woqkegr2j {
  fill: currentColor;
  d: path("M8 8h4l4 4 -4 4H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

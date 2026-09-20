<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rwa7yr8zy"/><path class="j8lijfbga"/><path class="wmtj7ubjb"/><path class="bw1nw8b2t"/><path class="wrji4lgnj"/><path class="f6186achz"/><path class="fg9400yys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:temperature-range-duotone-thin" /></template>
<style>
.bw1nw8b2t {
  d: path("M10 17.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.f6186achz {
  d: path("M15 8h4");
}

.fg9400yys {
  d: path("M15 13h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j8lijfbga {
  fill: currentColor;
  d: path("M10 17.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rwa7yr8zy {
  fill: currentColor;
  d: path("M9.5 15V6a2.5 2.5 0 0 1 5 0v9a4.5 4.5 0 1 1 -5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wmtj7ubjb {
  d: path("M9.5 15V6a2.5 2.5 0 0 1 5 0v9a4.5 4.5 0 1 1 -5 0");
}

.wrji4lgnj {
  d: path("M12 8v7");
}

</style>

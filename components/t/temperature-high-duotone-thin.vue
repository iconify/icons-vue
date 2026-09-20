<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iygs0sblg"/><path class="pwh-uhb6b"/><path class="le4-j1b7w"/><path class="rxj7i8-nj"/><path class="zbaxlgfvt"/><path class="j3gg_lb4w"/><path class="lkvhsog-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:temperature-high-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iygs0sblg {
  fill: currentColor;
  d: path("M9 6a3 3 0 0 1 3 -3 3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3 3 3 0 0 1 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.j3gg_lb4w {
  d: path("M16.5 6H19");
}

.le4-j1b7w {
  d: path("M9 6a3 3 0 0 1 3 -3 3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3 3 3 0 0 1 -3 -3Z");
}

.lkvhsog-e {
  d: path("M16.5 10H19");
}

.pwh-uhb6b {
  fill: currentColor;
  d: path("M9 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rxj7i8-nj {
  d: path("M9 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.zbaxlgfvt {
  d: path("M12 6v8.5");
}

</style>

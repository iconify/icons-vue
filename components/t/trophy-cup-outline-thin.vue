<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="as6g9lfvf"/><path class="s2f_5t2iz"/><path class="nbgsfjb6u"/><path class="tr6mw0eac"/><path class="jwnes9bsk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trophy-cup-outline-thin" /></template>
<style>
.as6g9lfvf {
  d: path("M7 3h10v6c0 4 -2 6 -5 6s-5 -2 -5 -6Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwnes9bsk {
  d: path("M8 19h8");
}

.nbgsfjb6u {
  d: path("M17 5c3 0 4 4 0 5");
}

.s2f_5t2iz {
  d: path("M7 5c-3 0 -4 4 0 5");
}

.tr6mw0eac {
  d: path("M12 15v4");
}

</style>

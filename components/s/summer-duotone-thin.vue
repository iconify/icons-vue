<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gfzmy-bgb"/><path class="gcurcebny"/><path class="af7iv3n-p"/><path class="x2yb-zrgu"/><path class="pu6yknsbt"/><path class="n6jttac-z"/><path class="f59axuhhu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:summer-duotone-thin" /></template>
<style>
.af7iv3n-p {
  d: path("M12 2v2.5");
}

.f59axuhhu {
  d: path("M4.5 4.5 7 7");
}

.gcurcebny {
  d: path("M6 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.gfzmy-bgb {
  fill: currentColor;
  d: path("M6 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
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

.n6jttac-z {
  d: path("M19.5 12H22");
}

.pu6yknsbt {
  d: path("M2 12h2.5");
}

.x2yb-zrgu {
  d: path("M12 19.5V22");
}

</style>

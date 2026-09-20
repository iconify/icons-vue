<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gr-2bmw8s"/><path class="zsdu4_bkp"/><path class="a-wplf-uj"/><path class="wd2ghz3oy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:turn-left-duotone-regular" /></template>
<style>
.a-wplf-uj {
  d: path("M16 21V9H7");
}

.gr-2bmw8s {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 21V9H7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wd2ghz3oy {
  d: path("M10 6 7 9l3 3");
}

.zsdu4_bkp {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 6 7 9l3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

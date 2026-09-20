<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r9xhy5bgz"/><path class="vos1yf-qb"/><path class="pxhtn-byk"/><path class="f5y0d7xbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trend-down-duotone-regular" /></template>
<style>
.f5y0d7xbc {
  d: path("M17 17h4v-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pxhtn-byk {
  d: path("m3 7 6 6 4 -4 8 8");
}

.r9xhy5bgz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 7 6 6 4 -4 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vos1yf-qb {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 17h4v-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zjwn55blz"/><path class="zkld0ib7h"/><path class="hgmedzbsm"/><path class="h2ryw2b8h"/><path class="szeqx6bdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:reading-list-duotone-regular" /></template>
<style>
.h2ryw2b8h {
  d: path("M13 13h7");
}

.hgmedzbsm {
  d: path("M13 9h7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.szeqx6bdv {
  d: path("M13 17h5");
}

.zjwn55blz {
  fill: currentColor;
  d: path("M4 6h6v10l-3 -3 -3 3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zkld0ib7h {
  d: path("M4 6h6v10l-3 -3 -3 3Z");
}

</style>

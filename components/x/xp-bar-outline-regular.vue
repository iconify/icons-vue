<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mh_3yqm3z"/><path class="mb3fb7bkl"/><path class="tdul-wdwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:xp-bar-outline-regular" /></template>
<style>
.mb3fb7bkl {
  d: path("M17 10v10");
}

.mh_3yqm3z {
  d: path("M3 10h18v10H3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tdul-wdwn {
  d: path("m9 6 3 -3 3 3");
}

</style>

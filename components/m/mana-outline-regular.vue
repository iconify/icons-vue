<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mh_3yqm3z"/><path class="mk-ueebig"/><path class="c0xrb9bxf"/><path class="t7ah1ybjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mana-outline-regular" /></template>
<style>
.c0xrb9bxf {
  d: path("m17 2 -3 3h3l-4 4");
}

.mh_3yqm3z {
  d: path("M3 10h18v10H3Z");
}

.mk-ueebig {
  d: path("M9 10v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t7ah1ybjn {
  d: path("M19 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>

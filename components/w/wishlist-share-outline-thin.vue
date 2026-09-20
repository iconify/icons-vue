<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vo1-lv2pt"/><path class="oz3eccbug"/><path class="o3jwr8bmt"/><path class="hldrv0d4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wishlist-share-outline-thin" /></template>
<style>
.hldrv0d4b {
  d: path("M11.5 12H15v3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o3jwr8bmt {
  d: path("m9 18 6 -6");
}

.oz3eccbug {
  d: path("M7 8a5 5 0 0 1 10 0");
}

.vo1-lv2pt {
  d: path("M3 10a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>

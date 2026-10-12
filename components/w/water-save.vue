<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wbgdyoepo"/><path class="eemhipsnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:water-save" /></template>
<style>
.eemhipsnm {
  d: path("M12 10.25v7m-2.5-2.5l2.5 2.5l2.5-2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wbgdyoepo {
  d: path("M12 2.75c3.75 4.25 6.25 8 6.25 12.25a6.25 6.25 0 0 1-12.5 0c0-4.25 2.5-8 6.25-12.25");
}

</style>

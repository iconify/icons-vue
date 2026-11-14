<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eur1fnb4e"/><path class="jsk2qyk6o"/><path class="eg04ujblc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-reuse" /></template>
<style>
.eg04ujblc {
  d: path("m20.5 19.5l-.75-3l-2.75.75M12 7.5S9 11 9 13.25a3 3 0 0 0 6 0C15 11 12 7.5 12 7.5");
}

.eur1fnb4e {
  d: path("M19.75 7.5a9 9 0 0 0-15.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jsk2qyk6o {
  d: path("m3.5 4.5l.75 3L7 6.75M4.25 16.5a9 9 0 0 0 15.5 0");
}

</style>

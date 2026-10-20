<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="kvu-e0bqx"/><path class="ljk_vcb1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vector-polygon-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kvu-e0bqx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 1L14 1C14.5523 1 15 1.4477 15 2L15 6C15 6.5523 14.5523 7 14 7L10 7C9.4477 7 9 6.5523 9 6L9 2C9 1.4477 9.4477 1 10 1ZM18 7L22 7C22.5523 7 23 7.4477 23 8L23 12C23 12.5523 22.5523 13 22 13L18 13C17.4477 13 17 12.5523 17 12L17 8C17 7.4477 17.4477 7 18 7ZM15 17L19 17C19.5523 17 20 17.4477 20 18L20 22C20 22.5523 19.5523 23 19 23L15 23C14.4477 23 14 22.5523 14 22L14 18C14 17.4477 14.4477 17 15 17ZM5 17L9 17C9.5523 17 10 17.4477 10 18L10 22C10 22.5523 9.5523 23 9 23L5 23C4.4477 23 4 22.5523 4 22L4 18C4 17.4477 4.4477 17 5 17ZM2 7L6 7C6.5523 7 7 7.4477 7 8L7 12C7 12.5523 6.5523 13 6 13L2 13C1.4477 13 1 12.5523 1 12L1 8C1 7.4477 1.4477 7 2 7Z");
  stroke: none;
}

.ljk_vcb1c {
  d: path("M14 5.5L18 8.5M19.4 12L17.6 18M15 20L9 20M6.4 18L4.6 12M6 8.5L10 5.5");
}

</style>

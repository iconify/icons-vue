<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jvwgfiiro"/><path class="hui23ybhi"/><path class="d2k5ylb_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:teepee" /></template>
<style>
.d2k5ylb_y {
  d: path("m12.2 13.46l3.1 7.33q.2.46-.3.46H9q-.5 0-.3-.46l3.1-7.33q.2-.46.4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hui23ybhi {
  d: path("m12.36 6.16l7.78 14.43q.36.66-.39.66H4.25q-.75 0-.39-.66l7.78-14.43q.36-.66.72 0M7.25 16.25h2.5m4.5 0h2.5");
}

.jvwgfiiro {
  d: path("M9.75 2.75L12 6.25l2.25-3.5");
}

</style>

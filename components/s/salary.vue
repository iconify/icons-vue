<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="s5qhcmbvd"/><path class="j5zatkbyh"/><circle class="mx0ir3bdi"/><path class="uffq2-buh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:salary" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j5zatkbyh {
  d: path("m7.25 16.25l4.75 2.5l4.75-2.5");
}

.mx0ir3bdi {
  cx: 12px;
  cy: 6.75px;
  r: 4px;
}

.s5qhcmbvd {
  width: 16.5px;
  height: 7.5px;
  x: 3.75px;
  y: 13.75px;
  rx: 2px;
}

.uffq2-buh {
  d: path("M13.13 5.77c-.21-.45-.62-.75-1.12-.75c-.67 0-1.17.39-1.17.86c0 1.22 2.34.61 2.34 1.78c0 .49-.5.83-1.17.83c-.52 0-.96-.28-1.14-.73");
}

</style>

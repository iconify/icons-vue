<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kq6wkvuhe"/><path class="j5zatkbyh"/><circle class="mx0ir3bdi"/><path class="le45whbbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:salary-sharp" /></template>
<style>
.j5zatkbyh {
  d: path("m7.25 16.25l4.75 2.5l4.75-2.5");
}

.kq6wkvuhe {
  d: path("M3.75 13.75h16.5v7.5H3.75z");
}

.le45whbbj {
  d: path("m13.13 5.77l-.35-.75h-1.94v.86c0 1.22 2.34.61 2.34 1.78v.83h-2.018l-.292-.73");
}

.mx0ir3bdi {
  cx: 12px;
  cy: 6.75px;
  r: 4px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

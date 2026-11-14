<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xfvk_5pjg"/><path class="br9p1dtsk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:race-lobby" /></template>
<style>
.br9p1dtsk {
  d: path("M6 13V5.75h8v5H6m4-5v5m-4-2.5h8m2 7.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.75 6c0-1.75 1.75-3 3.75-3s3.75 1.25 3.75 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xfvk_5pjg {
  d: path("M13.2 16H2.5V3h19v9.5M12 16v3.4m-3.5 1.1h3.1");
}

</style>

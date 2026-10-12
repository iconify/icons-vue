<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mf-mt79sn"/><path class="kqg1trbjd"/><circle class="c56lwnbsh"/><path class="hz4fdebup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:studio-monitor-sharp" /></template>
<style>
.c56lwnbsh {
  cx: 12px;
  cy: 13.25px;
  r: 2.75px;
}

.hz4fdebup {
  d: path("M12 18.5v2.75m-4 0h8");
}

.kqg1trbjd {
  d: path("M9.75 5.25h4.5v2.5h-4.5z");
}

.mf-mt79sn {
  d: path("M5.25 2.75h13.5V18.5H5.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

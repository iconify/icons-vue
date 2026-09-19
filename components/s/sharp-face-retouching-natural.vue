<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="t8-_arz4f"/><path class="rfuq4cb9x"/><circle class="pt3nek-ut"/><path class="m46fpw3lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-face-retouching-natural" /></template>
<style>
.m46fpw3lq {
  fill: currentColor;
  d: path("M20.6 5.6L19.5 8l-1.1-2.4L16 4.5l2.4-1.1L19.5 1l1.1 2.4L23 4.5z");
}

.pt3nek-ut {
  cx: 15px;
  cy: 13px;
  r: 1.25px;
  fill: currentColor;
}

.rfuq4cb9x {
  fill: currentColor;
  d: path("M19.85 10.59C20.79 15.4 17.01 20 12 20c-4.41 0-8-3.59-8-8c0-.39 3.87-1.12 5.74-5.69c3.42 4.19 8.07 3.73 9.09 3.59l-1.48-3.25l-4.72-2.15l3.5-1.59C9.51-.14 2 4.77 2 12c0 5.52 4.48 10 10 10c7.21 0 12.12-7.45 9.1-14.13z");
}

.t8-_arz4f {
  cx: 9px;
  cy: 13px;
  r: 1.25px;
  fill: currentColor;
}

</style>

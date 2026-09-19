<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="t8-_arz4f"/><circle class="pt3nek-ut"/><path class="c9shenbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-face-3" /></template>
<style>
.c9shenbpd {
  fill: currentColor;
  d: path("M22.91 11.96c-.54-5.93-5.75-10.41-11.8-9.92c-5.38.42-9.56 4.9-10.05 10.28L0 24h24zM4.54 9.13c.87.55 1.89.87 2.96.87c1.86 0 3.5-.93 4.5-2.35C13 9.07 14.64 10 16.5 10c1.07 0 2.09-.32 2.96-.87c.34.89.54 1.86.54 2.87c0 4.41-3.59 8-8 8s-8-3.59-8-8c0-1.01.2-1.98.54-2.87");
}

.pt3nek-ut {
  cx: 15px;
  cy: 13px;
  r: 1.25px;
  fill: currentColor;
}

.t8-_arz4f {
  cx: 9px;
  cy: 13px;
  r: 1.25px;
  fill: currentColor;
}

</style>

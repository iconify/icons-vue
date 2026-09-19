<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="t8-_arz4f"/><circle class="pt3nek-ut"/><path class="eto1twbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-face-3" /></template>
<style>
.eto1twbkl {
  fill: currentColor;
  d: path("M22.91 11.96C22.39 6.32 17.66 2 12 2S1.61 6.32 1.09 11.96l-.9 9.86c-.1 1.17.82 2.18 2 2.18h19.62c1.18 0 2.1-1.01 1.99-2.18zM4.54 9.13c.87.55 1.89.87 2.96.87c1.86 0 3.5-.93 4.5-2.35C13 9.07 14.64 10 16.5 10c1.07 0 2.09-.32 2.96-.87c.34.89.54 1.86.54 2.87c0 4.41-3.59 8-8 8s-8-3.59-8-8c0-1.01.2-1.98.54-2.87");
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

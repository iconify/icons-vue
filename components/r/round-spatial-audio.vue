<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpyl2tbla"/><circle class="guy77pi4w"/><path class="r8979-8va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-spatial-audio" /></template>
<style>
.guy77pi4w {
  cx: 10px;
  cy: 9px;
  r: 4px;
  fill: currentColor;
}

.r8979-8va {
  fill: currentColor;
  d: path("M16.39 15.56C14.71 14.7 12.53 14 10 14s-4.71.7-6.39 1.56A2.97 2.97 0 0 0 2 18.22V21h16v-2.78c0-1.12-.61-2.15-1.61-2.66");
}

.tpyl2tbla {
  fill: currentColor;
  d: path("M22.11 7.95c-1.89-.23-5.57-1.83-6.09-6.09a.976.976 0 0 0-.98-.86c-.6 0-1.07.53-1 1.13c.31 2.43 2.38 7.12 7.8 7.8c.6.08 1.13-.4 1.13-1c0-.5-.37-.92-.86-.98m-.4-2.12a1 1 0 0 0 1.26-.97c0-.47-.34-.85-.79-.97c-.49-.14-1.72-.68-2.11-2.13c-.12-.44-.5-.76-.96-.76h-.01c-.66 0-1.14.64-.96 1.28c.6 2.22 2.44 3.25 3.57 3.55");
}

</style>

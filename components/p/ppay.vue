<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGjmHfFeUv)" class="y-c58mbsb"/><defs><linearGradient id="SVGjmHfFeUv" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="eftuxgn0j"/><stop offset="1" class="l5alyhbmh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ppay" /></template>
<style>
.eftuxgn0j {
  stop-color: var(--svg-color--fb4440, #fb4440);
}

.ft5dv1b6b {
  fill: none;
}

.l5alyhbmh {
  stop-color: var(--svg-color--a72dc4, #a72dc4);
}

.y-c58mbsb {
  d: path("m21 10.982l-.017-.04L12 13.126c-3.156-.754-8.68-2.104-8.983-2.182L3 10.999C3.506 6.499 7.342 3 12 3c4.657 0 8.494 3.487 9 7.982m-.096 2.666L12 14.531l-8.904-.889a9.5 9.5 0 0 0 .495 1.71l8.409.585l8.381-.523a9 9 0 0 0 .523-1.766m-1.423 3.426q-3.736.249-7.481.27c-2.419-.023-5.794-.265-7.571-.405q.438.666.995 1.248h13.152q.496-.52.905-1.113m-2.2 2.238H6.713A9.06 9.06 0 0 0 12 21a9.05 9.05 0 0 0 5.282-1.688");
}

</style>

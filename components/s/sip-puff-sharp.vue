<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syg587jrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sip-puff-sharp" /></template>
<style>
.syg587jrs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.15 14.75v-2.12l-1.4-1.4V8.95c0-3.4 2.28-6.2 5.2-6.2c2.16 0 3.52 1.4 3.8 3.4l1.12 2.08l.2.52h-1.12v3.6h-2.4v2.4Zm8.8-5h5.3v4m-4.5 0h7.5v7.5h-7.5zm2 3.75h3.5");
}

</style>

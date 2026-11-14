<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg2m1-h-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scene-off" /></template>
<style>
.tg2m1-h-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3v5m-.951 7H5q0-.604.104-1.2q.103-.595.307-1.164q.204-.568.503-1.094q.298-.525.682-.992M11.977 8H12q.172 0 .343.008t.343.026q.171.017.341.042t.339.059q.168.033.335.075t.331.091q.164.05.326.108t.321.124t.314.139t.307.155t.299.169t.29.184q.143.095.281.198q.138.102.271.211t.26.224t.249.237t.237.249t.224.26t.211.271t.198.281t.184.29t.169.299t.155.307q.073.155.139.314t.124.321t.108.326t.091.331q.042.167.075.335q.034.169.059.339t.042.341t.026.343Q19 14.828 19 15h-.051M3.5 3.5l17 17");
}

</style>

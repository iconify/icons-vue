<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv8rdncyx"/><path class="kp097gb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-filter-frames" /></template>
<style>
.hv8rdncyx {
  fill: currentColor;
  d: path("M8 10h8v6H8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.kp097gb6u {
  fill: currentColor;
  d: path("M20 4h-4l-4-4l-4 4H4c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 16H4V6h4.52l3.52-3.5L15.52 6H20zM6 18h12V8H6zm2-8h8v6H8z");
}

</style>

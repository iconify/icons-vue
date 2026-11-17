<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zppcc9b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-alt-map-pin-corner-round" /></template>
<style>
.zppcc9b-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.394 10H12a1.16 1.16 0 0 1-1.008-1.736l2.016-3.528A1.16 1.16 0 0 0 12 3H8.3a2 2 0 0 0-1.828 1.188L3.61 10.629A.975.975 0 0 0 4.5 12c.77 0 1.342.713 1.175 1.464l-1.241 5.584c-.127.568.568.95.98.538l4.67-4.67M17 21c-1.5-1-3-3-3-5a3 3 0 0 1 6 0c0 2-1.5 4-3 5m0-5h.01");
}

</style>

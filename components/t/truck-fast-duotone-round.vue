<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zsjlvozqh"/><path class="bjbntfbsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:truck-fast-duotone-round" /></template>
<style>
.bjbntfbsr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 18a2 2 0 0 1-2-2M3 5h7a3 3 0 0 1 3 3v10m0-10h3c.64 0 1.36.36 2 1l2 2c.64.64 1 1.36 1 2v3a2 2 0 0 1-2 2M9 18h6m-2-6h7M3 9h6m-6 4h4m-2 5a2 2 0 1 0 4 0a2 2 0 0 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.ft5dv1b6b {
  fill: none;
}

.zsjlvozqh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 4a4.006 4.006 0 0 1 3.874 3H16c1.039 0 1.992.578 2.707 1.293l2 2C21.422 11.008 22 11.961 22 13v3c0 1.32-.866 2.487-2.128 2.872a3 3 0 0 1-5.701.128H9.829a3 3 0 0 1-5.7-.128A3.005 3.005 0 0 1 2 16V5a1 1 0 0 1 1-1ZM6.291 18.705l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 0 1.41m11.414.004l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 1.414 1.414");
}

</style>

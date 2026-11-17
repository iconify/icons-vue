<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s3e3qqpdz"/><path class="xx0r7gbdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paw-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.s3e3qqpdz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 10c2.516.002 3.655 2.27 5 4c.969 1.26 1.999 2.296 2 4c0 1.3-1.2 2-3 2c-1.5 0-2.5-1-4-1s-2.5 1-4 1c-1.8 0-3-.7-3-2c.001-1.704 1.031-2.74 2-4c1.345-1.73 2.484-3.998 5-4");
}

.xx0r7gbdh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10c2.5 0 3.6 2.2 5 4c1 1.3 2 2.3 2 4c0 1.3-1.2 2-3 2c-1.5 0-2.5-1-4-1s-2.5 1-4 1c-1.8 0-3-.7-3-2c0-1.7 1-2.7 2-4c1.4-1.8 2.5-4 5-4m-8 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m4-5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m4 5a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>

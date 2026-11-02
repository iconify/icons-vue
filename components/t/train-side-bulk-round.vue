<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="aabz0ybdn"/><path class="up-2ksnci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:train-side-bulk-round" /></template>
<style>
.aabz0ybdn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 16H7a5 5 0 0 1-5-5V7a3 3 0 0 1 3-3h6a11 11 0 0 1 8.8 4.4l.325.43c.465.615.945 1.231 1.305 1.915c.366.696.57 1.468.57 2.255c0 .797-.314 1.558-.879 2.121A3 3 0 0 1 19 16M4 8h4V6H5a1 1 0 0 0-1 1Zm6 0h6.657A9 9 0 0 0 11 6h-1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.up-2ksnci {
  d: path("M21 20H3a1 1 0 0 1 0-2h18a1 1 0 0 1 0 2");
}

</style>

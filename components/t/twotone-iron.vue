<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcu-r_z9u"/><path class="yixkk7odo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-iron" /></template>
<style>
.qcu-r_z9u {
  fill: currentColor;
  d: path("M15 16H4v-1c0-1.1.9-2 2-2h9z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.yixkk7odo {
  fill: currentColor;
  d: path("M21 6c-1.66 0-3 1.34-3 3v4c0 .55-.45 1-1 1v-4c0-1.66-1.34-3-3-3h-4c-1.66 0-3 1.34-3 3h2c0-.55.45-1 1-1h4c.55 0 1 .45 1 1v1H6c-2.21 0-4 1.79-4 4v3h15v-2c1.66 0 3-1.34 3-3V9c0-.55.45-1 1-1h1V6zm-6 10H4v-1c0-1.1.9-2 2-2h9z");
}

</style>

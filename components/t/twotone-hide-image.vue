<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi73isb5b"/><path class="bv0taos4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-hide-image" /></template>
<style>
.bv0taos4k {
  fill: currentColor;
  d: path("M19 5v11.17l2 2V5c0-1.1-.9-2-2-2H5.83l2 2zM2.81 2.81L1.39 4.22L3 5.83V19c0 1.1.9 2 2 2h13.17l1.61 1.61l1.41-1.41zM5 19V7.83l7.07 7.07l-.82 1.1L9 13l-3 4h8.17l2 2z");
}

.fi73isb5b {
  fill: currentColor;
  d: path("m16.17 19l-2-2H6l3-4l2.25 3l.82-1.1L5 7.83V19zM7.83 5L19 16.17V5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>

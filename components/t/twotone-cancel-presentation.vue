<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxl0gcc2m"/><path class="s2yuad98p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-cancel-presentation" /></template>
<style>
.kxl0gcc2m {
  fill: currentColor;
  d: path("M3 19.1h18V4.95H3zm5-9.74l1.41-1.41L12 10.54l2.59-2.59L16 9.36l-2.59 2.59L16 14.54l-1.41 1.41L12 13.36l-2.59 2.59L8 14.54l2.59-2.59z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.s2yuad98p {
  fill: currentColor;
  d: path("M21 3H3c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H3V5h18zM9.41 15.95L12 13.36l2.59 2.59L16 14.54l-2.59-2.59L16 9.36l-1.41-1.41L12 10.54L9.41 7.95L8 9.36l2.59 2.59L8 14.54z");
}

</style>

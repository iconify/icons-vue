<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyjz-ovza"/><path class="zv2ew-btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-arrow-circle-right" /></template>
<style>
.dyjz-ovza {
  fill: currentColor;
  d: path("M4 12c0-4.41 3.59-8 8-8s8 3.59 8 8s-3.59 8-8 8s-8-3.59-8-8m8-1H8v2h4v3l4-4l-4-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.zv2ew-btn {
  fill: currentColor;
  d: path("M4 12c0-4.41 3.59-8 8-8s8 3.59 8 8s-3.59 8-8 8s-8-3.59-8-8m-2 0c0 5.52 4.48 10 10 10s10-4.48 10-10S17.52 2 12 2S2 6.48 2 12m10-1H8v2h4v3l4-4l-4-4z");
}

</style>

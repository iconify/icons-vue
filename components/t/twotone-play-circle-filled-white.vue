<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpzdv3b-x"/><path class="cageyqbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-play-circle-filled-white" /></template>
<style>
.cageyqbjd {
  fill: currentColor;
  d: path("M12 22c5.52 0 10-4.48 10-10S17.52 2 12 2S2 6.48 2 12s4.48 10 10 10m0-18c4.41 0 8 3.59 8 8s-3.59 8-8 8s-8-3.59-8-8s3.59-8 8-8m-2 3.5v9l6-4.5z");
}

.fpzdv3b-x {
  fill: currentColor;
  d: path("M12 20c4.41 0 8-3.59 8-8s-3.59-8-8-8s-8 3.59-8 8s3.59 8 8 8M10 7.5l6 4.5l-6 4.5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>

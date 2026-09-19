<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fed74bbeq"/><path class="tgfe9klow"/><circle class="soci7ctjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-attribution" /></template>
<style>
.fed74bbeq {
  fill: currentColor;
  d: path("M12 4c-4.42 0-8 3.58-8 8s3.58 8 8 8s8-3.58 8-8s-3.58-8-8-8m0 1c.83 0 1.5.67 1.5 1.5S12.83 8 12 8s-1.5-.67-1.5-1.5S11.17 5 12 5m2.75 9.5h-1.5V19h-2.5v-4.5h-1.5V9.88c0-.92 1.84-1.38 2.75-1.38s2.75.47 2.75 1.38z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.soci7ctjl {
  cx: 12px;
  cy: 6.5px;
  r: 1.5px;
  fill: currentColor;
}

.tgfe9klow {
  fill: currentColor;
  d: path("M12 2C6.47 2 2 6.47 2 12s4.47 10 10 10s10-4.48 10-10S17.52 2 12 2m0 18c-4.42 0-8-3.58-8-8s3.58-8 8-8s8 3.58 8 8s-3.58 8-8 8m0-11.5c-.91 0-2.75.46-2.75 1.38v4.62h1.5V19h2.5v-4.5h1.5V9.88c0-.91-1.84-1.38-2.75-1.38");
}

</style>

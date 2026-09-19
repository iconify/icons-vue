<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsv4-lbxz"/><path class="gb-uq2sun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:signal-wifi-2-bar" /></template>
<style>
.gb-uq2sun {
  fill: currentColor;
  d: path("m4.79 12.52l7.2 8.98H12l.01-.01l7.2-8.98C18.85 12.24 16.1 10 12 10s-6.85 2.24-7.21 2.52");
}

.qsv4-lbxz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M12.01 21.49L23.64 7c-.45-.34-4.93-4-11.64-4C5.28 3 .81 6.66.36 7l11.63 14.49l.01.01z");
}

</style>

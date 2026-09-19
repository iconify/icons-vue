<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmw5srbfz"/><path class="hnbyaobjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-camera-rear" /></template>
<style>
.hnbyaobjq {
  fill: currentColor;
  d: path("M5 20v2h5v2l3-3l-3-3v2zm9 0h5v2h-5zm5-18c0-1.1-.9-2-2-2H7C5.9 0 5 .9 5 2v14c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2zm-2 14H7V2h10zm-5-9c1.1 0 2-.9 1.99-2c0-1.1-.9-2-2-2S10 3.9 10 5s.89 2 2 2");
}

.lmw5srbfz {
  fill: currentColor;
  d: path("M7 16h10V2H7zm4.99-13c1.1 0 2 .9 2 2C14 6.1 13.1 7 12 7c-1.11 0-2-.9-2-2s.89-2 1.99-2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>

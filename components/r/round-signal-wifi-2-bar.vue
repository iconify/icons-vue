<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aibtjkgta"/><path class="hs2ksxe4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-signal-wifi-2-bar" /></template>
<style>
.aibtjkgta {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M23.64 7c-.45-.34-4.93-4-11.64-4C5.28 3 .81 6.66.36 7l10.08 12.56c.8 1 2.32 1 3.12 0z");
}

.hs2ksxe4n {
  fill: currentColor;
  d: path("m4.79 12.52l5.65 7.04c.8 1 2.32 1 3.12 0l5.65-7.05C18.85 12.24 16.1 10 12 10s-6.85 2.24-7.21 2.52");
}

</style>

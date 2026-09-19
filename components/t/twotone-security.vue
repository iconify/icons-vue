<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8p0zpbvo"/><path class="e1y19lbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-security" /></template>
<style>
.e1y19lbhc {
  fill: currentColor;
  d: path("M12 1L3 5v6c0 5.55 3.84 10.74 9 12c5.16-1.26 9-6.45 9-12V5zm0 19.93V12H5V6.3l7-3.11v8.8h7c-.53 4.12-3.28 7.79-7 8.94");
}

.w8p0zpbvo {
  fill: currentColor;
  d: path("M12 3.19L5 6.3V12h7v8.93c3.72-1.15 6.47-4.82 7-8.94h-7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>

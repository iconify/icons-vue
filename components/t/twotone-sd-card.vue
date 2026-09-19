<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf7dyrd6k"/><path class="x71uk_lzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-sd-card" /></template>
<style>
.x71uk_lzd {
  fill: currentColor;
  d: path("M18 2h-8L4 8v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 18H6V8.83L10.83 4H18zM9 7h2v4H9zm3 0h2v4h-2zm3 0h2v4h-2z");
}

.xf7dyrd6k {
  fill: currentColor;
  d: path("M6 8.83V20h12V4h-7.17zM15 7h2v4h-2zm-3 0h2v4h-2zm-1 4H9V7h2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>

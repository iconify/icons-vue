<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzqoe6r8u"/><path class="ds-8v9beo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-propane-tank" /></template>
<style>
.ds-8v9beo {
  fill: currentColor;
  d: path("M17 6.14V4c0-1.1-.9-2-2-2H9c-1.1 0-2 .9-2 2v2.14c-1.72.45-3 2-3 3.86v8c0 2.21 1.79 4 4 4h8c2.21 0 4-1.79 4-4v-8c0-1.86-1.28-3.41-3-3.86M9 4h6v2h-2c0-.55-.45-1-1-1s-1 .45-1 1H9zm9 14c0 1.1-.9 2-2 2H8c-1.1 0-2-.9-2-2v-3h12zm0-5H6v-3c0-1.1.9-2 2-2h8c1.1 0 2 .9 2 2z");
}

.qzqoe6r8u {
  fill: currentColor;
  d: path("M6 18c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2v-3H6zM16 8H8c-1.1 0-2 .9-2 2v3h12v-3c0-1.1-.9-2-2-2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>

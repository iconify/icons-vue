<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trw9gcccf"/><path class="egejmmegx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-desktop-windows" /></template>
<style>
.egejmmegx {
  fill: currentColor;
  d: path("M21 2H3c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h7v2H8v2h8v-2h-2v-2h7c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 14H3V4h18z");
}

.trw9gcccf {
  fill: currentColor;
  d: path("M3 4h18v12H3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>

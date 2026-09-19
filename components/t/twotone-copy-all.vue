<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk6xxibxe"/><path class="mn29gw9as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-copy-all" /></template>
<style>
.mn29gw9as {
  fill: currentColor;
  d: path("M18 2H9c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h9c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 14H9V4h9zM3 15v-2h2v2zm0-5.5h2v2H3zM10 20h2v2h-2zm-7-1.5v-2h2v2zM5 22c-1.1 0-2-.9-2-2h2zm3.5 0h-2v-2h2zm5 0v-2h2c0 1.1-.9 2-2 2M5 6v2H3c0-1.1.9-2 2-2");
}

.qk6xxibxe {
  fill: currentColor;
  d: path("M9 4h9v12H9z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>

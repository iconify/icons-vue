<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oigv-rpao"/><path class="pdq_n1b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-featured-video" /></template>
<style>
.oigv-rpao {
  fill: currentColor;
  d: path("M3 19h18V5H3zM4 6h9v7H4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.pdq_n1b-b {
  fill: currentColor;
  d: path("M21 3H3c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H3V5h18zM4 6h9v7H4z");
}

</style>

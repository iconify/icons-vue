<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbe44ackq"/><path class="ut850xomt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-explicit" /></template>
<style>
.cbe44ackq {
  fill: currentColor;
  d: path("M5 19h14V5H5zM9 7h6v2h-4v2h4v2h-4v2h4v2H9z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ut850xomt {
  fill: currentColor;
  d: path("M21 19V5c0-1.1-.9-2-2-2H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2m-2 0H5V5h14zm-4-4h-4v-2h4v-2h-4V9h4V7H9v10h6z");
}

</style>

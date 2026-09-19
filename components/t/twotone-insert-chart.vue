<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lphnu4tod"/><path class="izswi-b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-insert-chart" /></template>
<style>
.izswi-b0m {
  fill: currentColor;
  d: path("M3 5v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2H5c-1.1 0-2 .9-2 2m2 0h14v14H5zm2 5h2v7H7zm4-3h2v10h-2zm4 6h2v4h-2z");
}

.lphnu4tod {
  fill: currentColor;
  d: path("M19 5H5v14h14zM9 17H7v-7h2zm4 0h-2V7h2zm4 0h-2v-4h2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>

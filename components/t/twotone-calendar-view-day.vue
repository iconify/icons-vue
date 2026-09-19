<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2grdbctc"/><path class="w67i_9pqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-calendar-view-day" /></template>
<style>
.i2grdbctc {
  fill: currentColor;
  d: path("M3 17h18v2H3zm16-5v1H5v-1zm2-2H3v5h18zM3 6h18v2H3z");
}

.w67i_9pqg {
  fill: currentColor;
  d: path("M5 12h14v1H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>

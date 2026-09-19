<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdbjo-bzb"/><path class="zybicnbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-view-array" /></template>
<style>
.zdbjo-bzb {
  fill: currentColor;
  d: path("M9 7h6v10H9z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.zybicnbwc {
  fill: currentColor;
  d: path("M15 7v10H9V7zm6-2h-3v14h3zm-4 0H7v14h10zM6 5H3v14h3z");
}

</style>

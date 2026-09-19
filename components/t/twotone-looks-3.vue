<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkhmfe28m"/><path class="asdyf3o-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-looks-3" /></template>
<style>
.asdyf3o-j {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14zm-4-4v-1.5c0-.83-.67-1.5-1.5-1.5c.83 0 1.5-.67 1.5-1.5V9a2 2 0 0 0-2-2H9v2h4v2h-2v2h2v2H9v2h4a2 2 0 0 0 2-2");
}

.bkhmfe28m {
  fill: currentColor;
  d: path("M5 19h14V5H5zm4-4h4v-2h-2v-2h2V9H9V7h4a2 2 0 0 1 2 2v1.5c0 .83-.67 1.5-1.5 1.5c.83 0 1.5.67 1.5 1.5V15a2 2 0 0 1-2 2H9z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxp5dfuyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ratio-9-16-bulk-round" /></template>
<style>
.cxp5dfuyw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 7a5 5 0 0 1 5-5h2a5 5 0 0 1 5 5v10a5 5 0 0 1-5 5h-2a5 5 0 0 1-5-5Z");
}

</style>

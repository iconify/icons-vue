<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umke7jbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pause-bulk-sharp" /></template>
<style>
.umke7jbsf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 2h5a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1m11 0h5a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

</style>

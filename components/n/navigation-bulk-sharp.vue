<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shw3olbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:navigation-bulk-sharp" /></template>
<style>
.shw3olbgu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m3.316 2.051l18 6a1 1 0 0 1 .131 1.843l-7.702 3.851l-3.851 7.702a1 1 0 0 1-1.843-.131l-6-18a1.001 1.001 0 0 1 1.265-1.265");
}

</style>

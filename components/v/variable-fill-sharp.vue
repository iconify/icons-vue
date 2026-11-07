<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4hnijb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:variable-fill-sharp" /></template>
<style>
.n4hnijb8r {
  fill: currentColor;
  d: path("M7.707 5.707c-3.607 3.609-3.607 8.977 0 12.586a1 1 0 1 1-1.414 1.414c-4.388-4.39-4.388-11.024 0-15.414a.999.999 0 1 1 1.414 1.414m10-1.414c4.388 4.39 4.388 11.024 0 15.414a.999.999 0 1 1-1.414-1.414a9.3 9.3 0 0 0 2.035-2.994A8.4 8.4 0 0 0 19 12c0-2.396-1.025-4.61-2.707-6.293a.999.999 0 1 1 1.414-1.414m-8 4L12 10.586l2.293-2.293a.999.999 0 1 1 1.414 1.414L13.414 12l2.293 2.293a.999.999 0 1 1-1.414 1.414L12 13.414l-2.293 2.293a.999.999 0 1 1-1.414-1.414L10.586 12L8.293 9.707a.999.999 0 1 1 1.414-1.414");
}

</style>

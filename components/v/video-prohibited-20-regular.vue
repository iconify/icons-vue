<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o482f4b2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-prohibited-20-regular" /></template>
<style>
.o482f4b2z {
  fill: currentColor;
  d: path("M5.5 9a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m-2.096 7.303a3.5 3.5 0 0 0 4.898-4.898zM10 4a3 3 0 0 1 3 3v.32l3.037-2.096a1.25 1.25 0 0 1 1.96 1.028v7.495a1.25 1.25 0 0 1-1.96 1.028L13 12.68V13a3 3 0 0 1-2.587 2.97q.277-.548.428-1.158A2 2 0 0 0 12 13V7a2 2 0 0 0-2-2H5a2 2 0 0 0-2 2v1.6a5.5 5.5 0 0 0-1 .657V7a3 3 0 0 1 3-3zm-4.5 6a3.5 3.5 0 0 0-2.803 5.596l4.899-4.899A3.5 3.5 0 0 0 5.5 10m11.497-3.748a.25.25 0 0 0-.392-.205L13 8.537v2.927l3.605 2.49a.25.25 0 0 0 .392-.207z");
}

</style>

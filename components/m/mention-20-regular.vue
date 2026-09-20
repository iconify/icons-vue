<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w8c836b1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mention-20-regular" /></template>
<style>
.w8c836b1w {
  fill: currentColor;
  d: path("M10 2a8 8 0 0 1 8 8c0 2.5-1.378 3.996-3 3.996c-1.071 0-2.036-.652-2.567-1.815C11.82 13.26 10.76 14 9.5 14C7.497 14 6 12.134 6 10s1.497-4 3.5-4c1 0 1.875.466 2.5 1.198V6.5a.5.5 0 0 1 1 0V10l.013.39c.126 1.872 1.164 2.606 1.987 2.606c.878 0 2-.835 2-2.996a7 7 0 1 0-4.712 6.614a.54.54 0 0 1 .559.121c.253.253.176.68-.16.8A8 8 0 1 1 10 2m-.5 5C8.189 7 7 8.268 7 10s1.189 3 2.5 3s2.5-1.268 2.5-3s-1.189-3-2.5-3");
}

</style>

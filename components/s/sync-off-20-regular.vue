<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="flla8_tbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sync-off-20-regular" /></template>
<style>
.flla8_tbb {
  fill: currentColor;
  d: path("M2 10a8 8 0 1 1 16 0a8 8 0 0 1-16 0m8-7a7 7 0 0 0-6.93 6h5.196l.753-2.638a.5.5 0 1 1 .962.275l-2 7a.5.5 0 1 1-.962-.275L7.98 10H3a7 7 0 1 0 14 0h-4.98l-1.04 3.637a.5.5 0 1 1-.96-.275l2-7a.5.5 0 1 1 .96.275L12.307 9h4.623A7 7 0 0 0 10 3");
}

</style>

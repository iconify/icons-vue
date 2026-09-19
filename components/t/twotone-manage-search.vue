<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7ytgzbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-manage-search" /></template>
<style>
.k7ytgzbek {
  fill: currentColor;
  d: path("M2 12h5v2H2zm16.17 1.75c.52-.79.83-1.73.83-2.75c0-2.76-2.24-5-5-5s-5 2.24-5 5s2.24 5 5 5c1.02 0 1.96-.31 2.76-.83L20.59 19L22 17.59zM14 14c-1.65 0-3-1.35-3-3s1.35-3 3-3s3 1.35 3 3s-1.35 3-3 3M2 7h5v2H2zm0 10h10v2H2z");
}

</style>

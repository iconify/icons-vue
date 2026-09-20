<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ur1m6_fjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:work-iq-16-regular" /></template>
<style>
.ur1m6_fjy {
  fill: currentColor;
  d: path("M8 2a7 7 0 0 1 7 7a4 4 0 0 1-3 3.874V13a2 2 0 0 0 2 2h.5a.5.5 0 0 1 0 1H14a3 3 0 0 1-3-3H9.5a2.5 2.5 0 1 1 2.5-2.5v1.325c1.165-.412 2-1.52 2-2.825A6 6 0 0 0 2 9a2 2 0 0 0 2 2h1a.5.5 0 0 1 0 1H4a3 3 0 0 1-3-3a7 7 0 0 1 7-7m1.5 7a1.5 1.5 0 1 0 0 3H11v-1.5A1.5 1.5 0 0 0 9.5 9");
}

</style>

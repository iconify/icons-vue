<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mpa1x5bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:temperature-20-regular" /></template>
<style>
.mpa1x5bhs {
  fill: currentColor;
  d: path("M10 6.5a.5.5 0 0 1 .5.5v5.063a2 2 0 1 1-1 0V7a.5.5 0 0 1 .5-.5M10 2a3 3 0 0 0-3 3v6.354a4 4 0 1 0 6 0V5a3 3 0 0 0-3-3m0 1a2 2 0 0 1 2 2v6.755l.143.145a3 3 0 1 1-4.286 0L8 11.755V5a2 2 0 0 1 2-2");
}

</style>

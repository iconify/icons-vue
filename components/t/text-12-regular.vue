<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="u_tahz86b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-12-regular" /></template>
<style>
.u_tahz86b {
  fill: currentColor;
  d: path("M2 2.5a.5.5 0 0 1 .5-.5h6a.5.5 0 0 1 .5.5V4a.5.5 0 0 1-1 0V3H6v6h.5a.5.5 0 0 1 0 1h-2a.5.5 0 0 1 0-1H5V3H3v1a.5.5 0 0 1-1 0z");
}

</style>

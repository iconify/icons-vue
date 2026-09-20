<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="g9ffsf90p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-color-accent-20-regular" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g9ffsf90p {
  d: path("M4 13.5a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 .5.5v3a.5.5 0 0 1-.5.5h-11a.5.5 0 0 1-.5-.5v-3z");
  fill: currentColor;
}

</style>

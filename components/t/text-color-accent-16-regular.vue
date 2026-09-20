<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ft5dv1b6b"><path class="qsk660iju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-color-accent-16-regular" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qsk660iju {
  d: path("M3 11.5a.5.5 0 0 1 .5-.5h9a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5v-2z");
  fill: currentColor;
}

</style>

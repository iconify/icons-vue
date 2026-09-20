<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jrqj6lrzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-clip-48-regular" /></template>
<style>
.jrqj6lrzt {
  fill: currentColor;
  d: path("M10.25 8A6.25 6.25 0 0 0 4 14.25v19.5A6.25 6.25 0 0 0 10.25 40h27.5A6.25 6.25 0 0 0 44 33.75v-19.5A6.25 6.25 0 0 0 37.75 8zM6.5 14.25a3.75 3.75 0 0 1 3.75-3.75h27.5a3.75 3.75 0 0 1 3.75 3.75v19.5a3.75 3.75 0 0 1-3.75 3.75h-27.5a3.75 3.75 0 0 1-3.75-3.75zM18 18v12a1.5 1.5 0 0 0 2.218 1.317l11-6a1.5 1.5 0 0 0 0-2.634l-11-6A1.5 1.5 0 0 0 18 18");
}

</style>

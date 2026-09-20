<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uv0367b0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sport-cricket-ball-16-regular" /></template>
<style>
.uv0367b0k {
  fill: currentColor;
  d: path("M8 1a6.99 6.99 0 0 1 5.831 3.128q.102.091.145.226A7 7 0 1 1 8 1m0 1a6 6 0 0 0-3.998 10.473A.5.5 0 0 1 4.5 12h1a.5.5 0 0 1 0 1h-.816a6 6 0 0 0 8.512-8H12.5a.5.5 0 0 1-.027-.998A5.98 5.98 0 0 0 8 2M4.5 9a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-1 0v-1a.5.5 0 0 1 .5-.5m3 1a.5.5 0 0 1 0 1h-1a.5.5 0 0 1 0-1zm-1-3a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-1 0v-1a.5.5 0 0 1 .5-.5m3 1a.5.5 0 0 1 0 1h-1a.5.5 0 0 1 0-1zm-1-3a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-1 0v-1a.5.5 0 0 1 .5-.5m3 1a.5.5 0 0 1 0 1h-1a.5.5 0 0 1 0-1zm-1-3a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-1 0v-1a.5.5 0 0 1 .5-.5");
}

</style>

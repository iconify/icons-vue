<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="jj4lf-ndj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:subtract-circle-12-regular" /></template>
<style>
.jj4lf-ndj {
  fill: currentColor;
  d: path("M4 5.5a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1zM6 1a5 5 0 1 0 0 10A5 5 0 0 0 6 1M2 6a4 4 0 1 1 8 0a4 4 0 0 1-8 0");
}

</style>

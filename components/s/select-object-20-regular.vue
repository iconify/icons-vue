<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="flc_xbzfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:select-object-20-regular" /></template>
<style>
.flc_xbzfd {
  fill: currentColor;
  d: path("M6 4.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m11 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m-11 11a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m11 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0M7 4.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5m0 11a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5m-3-8a.5.5 0 0 1 1 0v5a.5.5 0 0 1-1 0zm11 0a.5.5 0 0 1 1 0v5a.5.5 0 0 1-1 0z");
}

</style>

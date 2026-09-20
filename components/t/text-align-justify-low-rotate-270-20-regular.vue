<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dtn3bvb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-justify-low-rotate-270-20-regular" /></template>
<style>
.dtn3bvb9s {
  fill: currentColor;
  d: path("M4.5 11a.5.5 0 0 1-.5-.5v-8a.5.5 0 0 1 1 0v8a.5.5 0 0 1-.5.5m5 0a.5.5 0 0 1-.5-.5v-8a.5.5 0 0 1 1 0v8a.5.5 0 0 1-.5.5m4.5 6.5a.5.5 0 0 0 1 0v-15a.5.5 0 0 0-1 0z");
}

</style>

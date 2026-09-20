<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w6ajf4b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-justify-rotate-270-20-regular" /></template>
<style>
.w6ajf4b2b {
  fill: currentColor;
  d: path("M4.5 18a.5.5 0 0 1-.5-.5v-15a.5.5 0 0 1 1 0v15a.5.5 0 0 1-.5.5m5 0a.5.5 0 0 1-.5-.5v-15a.5.5 0 0 1 1 0v15a.5.5 0 0 1-.5.5m4.5-.5a.5.5 0 0 0 1 0v-15a.5.5 0 0 0-1 0z");
}

</style>

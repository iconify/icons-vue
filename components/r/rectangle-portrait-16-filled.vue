<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gljddutro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rectangle-portrait-16-filled" /></template>
<style>
.gljddutro {
  fill: currentColor;
  d: path("M3 12.5A2.5 2.5 0 0 0 5.5 15h5a2.5 2.5 0 0 0 2.5-2.5v-9A2.5 2.5 0 0 0 10.5 1h-5A2.5 2.5 0 0 0 3 3.5z");
}

</style>

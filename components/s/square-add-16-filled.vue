<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="waih8xbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:square-add-16-filled" /></template>
<style>
.waih8xbvj {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5v7A2.5 2.5 0 0 0 4.5 14h1.757A5.5 5.5 0 0 1 14 6.257V4.5A2.5 2.5 0 0 0 11.5 2zm6 13a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m0-7a.5.5 0 0 1 .5.5V10h1.5a.5.5 0 0 1 0 1H11v1.5a.5.5 0 0 1-1 0V11H8.5a.5.5 0 0 1 0-1H10V8.5a.5.5 0 0 1 .5-.5");
}

</style>

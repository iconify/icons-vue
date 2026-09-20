<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y724mwbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-pagination-24-filled" /></template>
<style>
.y724mwbyd {
  fill: currentColor;
  d: path("M15.75 2A2.25 2.25 0 0 1 18 4.25v15.5A2.25 2.25 0 0 1 15.75 22h-7.5A2.25 2.25 0 0 1 6 19.75V4.25A2.25 2.25 0 0 1 8.25 2zM9.499 17.762a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5m2.5 0a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5m2.5 0a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5");
}

</style>

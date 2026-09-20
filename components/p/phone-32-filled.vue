<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yv8kk6pdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-32-filled" /></template>
<style>
.yv8kk6pdq {
  fill: currentColor;
  d: path("M10.25 2A3.25 3.25 0 0 0 7 5.25v21.5A3.25 3.25 0 0 0 10.25 30h11.5A3.25 3.25 0 0 0 25 26.75V5.25A3.25 3.25 0 0 0 21.75 2zM14 24h4a1 1 0 1 1 0 2h-4a1 1 0 1 1 0-2");
}

</style>

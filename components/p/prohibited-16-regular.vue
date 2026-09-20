<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="toh0lpxph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:prohibited-16-regular" /></template>
<style>
.toh0lpxph {
  fill: currentColor;
  d: path("M11.875 3.418a6 6 0 0 0-8.457 8.457zm.707.707l-8.457 8.457a6 6 0 0 0 8.457-8.457M3.05 3.05a7 7 0 1 1 9.9 9.9a7 7 0 0 1-9.9-9.9");
}

</style>

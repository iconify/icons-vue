<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ulowq1ssn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:teardrop-bottom-right-20-regular" /></template>
<style>
.ulowq1ssn {
  fill: currentColor;
  d: path("M2 10a8 8 0 1 1 16 0v6a2 2 0 0 1-2 2h-6a8 8 0 0 1-8-8m8-7a7 7 0 0 0 0 14h6a1 1 0 0 0 1-1v-6a7 7 0 0 0-7-7");
}

</style>

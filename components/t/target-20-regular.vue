<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eacs1ubqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:target-20-regular" /></template>
<style>
.eacs1ubqs {
  fill: currentColor;
  d: path("M10 11.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3M5 10a5 5 0 1 1 10 0a5 5 0 0 1-10 0m5-4a4 4 0 1 0 0 8a4 4 0 0 0 0-8m-8 4a8 8 0 1 1 16 0a8 8 0 0 1-16 0m8-7a7 7 0 1 0 0 14a7 7 0 0 0 0-14");
}

</style>

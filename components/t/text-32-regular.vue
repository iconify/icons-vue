<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a7qsij1qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-32-regular" /></template>
<style>
.a7qsij1qn {
  fill: currentColor;
  d: path("M6 5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v4a1 1 0 1 1-2 0V6h-7v20h2a1 1 0 1 1 0 2h-6a1 1 0 1 1 0-2h2V6H8v3a1 1 0 0 1-2 0z");
}

</style>

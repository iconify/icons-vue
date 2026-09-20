<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fa_3chbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rectangle-portrait-32-regular" /></template>
<style>
.fa_3chbbr {
  fill: currentColor;
  d: path("M8.5 30A4.5 4.5 0 0 1 4 25.5v-19A4.5 4.5 0 0 1 8.5 2h15A4.5 4.5 0 0 1 28 6.5v19a4.5 4.5 0 0 1-4.5 4.5zM6 25.5A2.5 2.5 0 0 0 8.5 28h15a2.5 2.5 0 0 0 2.5-2.5v-19A2.5 2.5 0 0 0 23.5 4h-15A2.5 2.5 0 0 0 6 6.5z");
}

</style>

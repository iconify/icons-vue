<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="brj1p7r3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rectangle-portrait-32-filled" /></template>
<style>
.brj1p7r3b {
  fill: currentColor;
  d: path("M8.5 30A4.5 4.5 0 0 1 4 25.5v-19A4.5 4.5 0 0 1 8.5 2h15A4.5 4.5 0 0 1 28 6.5v19a4.5 4.5 0 0 1-4.5 4.5z");
}

</style>

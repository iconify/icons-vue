<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibwrqgbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:near-me-outline" /></template>
<style>
.ibwrqgbfk {
  fill: currentColor;
  d: path("m12.9 21l-2.85-7.05L3 11.1V9.7L21 3l-6.7 18zm.65-3.7L17.6 6.4L6.7 10.45l4.9 1.95zm-1.95-4.9");
}

</style>

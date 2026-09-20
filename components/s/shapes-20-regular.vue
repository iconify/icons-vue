<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iv1ikmwwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shapes-20-regular" /></template>
<style>
.iv1ikmwwh {
  fill: currentColor;
  d: path("M7.5 3a4.5 4.5 0 0 0-.5 8.973v1.005A5.5 5.5 0 1 1 12.978 7h-1.005A4.5 4.5 0 0 0 7.5 3m3 5A2.5 2.5 0 0 0 8 10.5v5a2.5 2.5 0 0 0 2.5 2.5h5a2.5 2.5 0 0 0 2.5-2.5v-5A2.5 2.5 0 0 0 15.5 8zM9 10.5A1.5 1.5 0 0 1 10.5 9h5a1.5 1.5 0 0 1 1.5 1.5v5a1.5 1.5 0 0 1-1.5 1.5h-5A1.5 1.5 0 0 1 9 15.5z");
}

</style>

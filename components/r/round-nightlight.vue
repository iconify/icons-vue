<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7ae85pta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-nightlight" /></template>
<style>
.o7ae85pta {
  fill: currentColor;
  d: path("M11.57 2.3c2.38-.59 4.68-.27 6.63.64c.35.16.41.64.1.86C15.7 5.6 14 8.6 14 12s1.7 6.4 4.3 8.2c.32.22.26.7-.09.86c-1.28.6-2.71.94-4.21.94c-6.05 0-10.85-5.38-9.87-11.6c.61-3.92 3.59-7.16 7.44-8.1");
}

</style>

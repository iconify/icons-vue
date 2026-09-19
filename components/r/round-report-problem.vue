<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc29o0ozu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-report-problem" /></template>
<style>
.nc29o0ozu {
  fill: currentColor;
  d: path("M2.73 21h18.53c.77 0 1.25-.83.87-1.5l-9.27-16a.996.996 0 0 0-1.73 0l-9.27 16c-.38.67.1 1.5.87 1.5M13 18h-2v-2h2zm-1-4c-.55 0-1-.45-1-1v-2c0-.55.45-1 1-1s1 .45 1 1v2c0 .55-.45 1-1 1");
}

</style>

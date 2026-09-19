<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy4eecebt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-border-color" /></template>
<style>
.jy4eecebt {
  fill: currentColor;
  d: path("m16.81 8.94l-3.75-3.75L4 14.25V18h3.75zM6 16v-.92l7.06-7.06l.92.92L6.92 16zm13.71-9.96a.996.996 0 0 0 0-1.41l-2.34-2.34a1 1 0 0 0-1.41 0l-1.83 1.83l3.75 3.75zM2 20h20v4H2z");
}

</style>

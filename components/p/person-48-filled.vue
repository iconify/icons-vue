<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aafn6dbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-48-filled" /></template>
<style>
.aafn6dbfv {
  fill: currentColor;
  d: path("M24 4c-5.523 0-10 4.477-10 10s4.477 10 10 10s10-4.477 10-10S29.523 4 24 4M12.25 28A4.25 4.25 0 0 0 8 32.249V33c0 3.755 1.942 6.567 4.92 8.38C15.85 43.163 19.786 44 24 44s8.15-.837 11.08-2.62C38.058 39.567 40 36.755 40 33v-.751A4.25 4.25 0 0 0 35.75 28z");
}

</style>

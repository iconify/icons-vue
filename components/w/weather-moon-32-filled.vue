<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u952rp-3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:weather-moon-32-filled" /></template>
<style>
.u952rp-3w {
  fill: currentColor;
  d: path("M2.854 22.965c-.539-.938.21-1.965 1.15-1.965c6.627 0 12-5.373 12-12c0-1.43-.25-2.8-.708-4.07a2.12 2.12 0 0 1 .254-1.934a1.88 1.88 0 0 1 1.883-.785C24.006 3.363 29.001 9.097 29.001 16c0 7.732-6.268 14-14 14a14 14 0 0 1-12.147-7.035");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a35x74n-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:paint-brush-subtract-24-regular" /></template>
<style>
.a35x74n-d {
  fill: currentColor;
  d: path("M5.75 2a.75.75 0 0 0-.75.75v11.5a2.25 2.25 0 0 0 2.25 2.25H9.5v3a2.5 2.5 0 0 0 3.213 2.397a6.5 6.5 0 0 1-1.003-1.44A1 1 0 0 1 11 19.5v-3.75a.75.75 0 0 0-.75-.75h-3a.75.75 0 0 1-.75-.75V12.5h6.846a6.47 6.47 0 0 1 4.09-1.5H6.5V3.5h6v1.752a.75.75 0 1 0 1.5 0V3.5h1v2.751a.75.75 0 1 0 1.5 0V3.5h1V11q.776.002 1.5.174V2.75a.75.75 0 0 0-.75-.75zM17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m2.997 6a.5.5 0 0 0 0-1h-6.001a.5.5 0 0 0 0 1z");
}

</style>

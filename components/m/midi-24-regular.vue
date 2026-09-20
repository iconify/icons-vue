<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-qgd1bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:midi-24-regular" /></template>
<style>
.b-qgd1bmi {
  fill: currentColor;
  d: path("M19.75 4A2.25 2.25 0 0 1 22 6.25v11.5A2.25 2.25 0 0 1 19.75 20H4.25A2.25 2.25 0 0 1 2 17.75V6.25A2.25 2.25 0 0 1 4.25 4zM3.5 17.75c0 .414.336.75.75.75h15.5a.75.75 0 0 0 .75-.75V12H18v4.25a.75.75 0 0 1-1.5 0V12h-2v4.25a.75.75 0 0 1-1.5 0V12h-2v4.25a.75.75 0 0 1-1.5 0V12h-2v4.25a.75.75 0 0 1-1.5 0V12H3.5zM4.25 5.5a.75.75 0 0 0-.75.75v4.25h17V6.25a.75.75 0 0 0-.75-.75zM6 7a1 1 0 1 1 0 2a1 1 0 0 1 0-2m3.5 0a1 1 0 1 1 0 2a1 1 0 0 1 0-2m7.75 0a.75.75 0 0 1 0 1.5h-2.5a.75.75 0 0 1 0-1.5z");
}

</style>

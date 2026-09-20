<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b76o_ic9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-underline-character-u-24-regular" /></template>
<style>
.b76o_ic9k {
  fill: currentColor;
  d: path("M8.5 4.75a.75.75 0 0 0-1.5 0V12a5 5 0 0 0 10 0V4.75a.75.75 0 0 0-1.5 0V12a3.5 3.5 0 1 1-7 0zM6.75 18.5a.75.75 0 0 0 0 1.5h10.5a.75.75 0 0 0 0-1.5z");
}

</style>

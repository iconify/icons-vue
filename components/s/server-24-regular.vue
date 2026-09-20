<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnxjrzizi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:server-24-regular" /></template>
<style>
.mnxjrzizi {
  fill: currentColor;
  d: path("M9.25 6a.75.75 0 0 0 0 1.5h5.5a.75.75 0 0 0 0-1.5zM8.5 17.75a.75.75 0 0 1 .75-.75h5.5a.75.75 0 0 1 0 1.5h-5.5a.75.75 0 0 1-.75-.75M9.25 14a.75.75 0 0 0 0 1.5h5.5a.75.75 0 0 0 0-1.5zM6 5a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3zm3-1.5A1.5 1.5 0 0 0 7.5 5v14A1.5 1.5 0 0 0 9 20.5h6a1.5 1.5 0 0 0 1.5-1.5V5A1.5 1.5 0 0 0 15 3.5z");
}

</style>

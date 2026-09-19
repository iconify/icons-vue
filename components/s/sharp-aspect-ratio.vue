<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1vuwrr9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-aspect-ratio" /></template>
<style>
.j1vuwrr9x {
  fill: currentColor;
  d: path("M19 12h-2v3h-3v2h5zM7 9h3V7H5v5h2zm16-6H1v18h22zm-2 16.01H3V4.99h18z");
}

</style>

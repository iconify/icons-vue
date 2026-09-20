<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u_3jk4z6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:number-circle-4-20-filled" /></template>
<style>
.u_3jk4z6e {
  fill: currentColor;
  d: path("M2 10a8 8 0 1 1 16 0a8 8 0 0 1-16 0m9.995-3.691c0-.738-.954-1.032-1.37-.423l-3.533 5.176a.6.6 0 0 0 .496.938h3.41v1.5a.5.5 0 0 0 1 0V12H13a.5.5 0 0 0 0-1h-1.003zm-1 .809L10.997 11H8.345z");
}

</style>

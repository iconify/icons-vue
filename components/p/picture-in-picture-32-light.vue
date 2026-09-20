<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="voxutqb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:picture-in-picture-32-light" /></template>
<style>
.voxutqb2m {
  fill: currentColor;
  d: path("M6.5 3A4.5 4.5 0 0 0 2 7.5v15A4.5 4.5 0 0 0 6.5 27h8.229q-.152-.481-.204-1H6.5A3.5 3.5 0 0 1 3 22.5v-15A3.5 3.5 0 0 1 6.5 4h19A3.5 3.5 0 0 1 29 7.5v8.229q.53.167 1 .44V7.5A4.5 4.5 0 0 0 25.5 3zM16 20.5a3.5 3.5 0 0 1 3.5-3.5h8a3.5 3.5 0 0 1 3.5 3.5v5a3.5 3.5 0 0 1-3.5 3.5h-8a3.5 3.5 0 0 1-3.5-3.5z");
}

</style>

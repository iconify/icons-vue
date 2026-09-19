<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ida42ny2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-expand" /></template>
<style>
.ida42ny2f {
  fill: currentColor;
  d: path("M4 20h16v2H4zM4 2h16v2H4zm5.41 11.59L8 15l4 4l4-4l-1.41-1.41L13 15.17V8.83l1.59 1.58L16 9l-4-4l-4 4l1.41 1.41L11 8.83v6.34z");
}

</style>

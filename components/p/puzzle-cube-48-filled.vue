<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f-qf15bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:puzzle-cube-48-filled" /></template>
<style>
.f-qf15bix {
  fill: currentColor;
  d: path("M19 6v10.5h10V6zm-2.5 13H6v10h10.5zM19 29V19h10v10zm-2.5 2.5H6v4.25A6.25 6.25 0 0 0 12.25 42h4.25zM19 42h10V31.5H19zm12.5 0V31.5H42v4.25A6.25 6.25 0 0 1 35.75 42zM42 19v10H31.5V19zm0-2.5v-4.25A6.25 6.25 0 0 0 35.75 6H31.5v10.5z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khand1ldd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stacked-bar-chart-outline" /></template>
<style>
.khand1ldd {
  fill: currentColor;
  d: path("M5 19V8.77h3V19zM5 8V5h3v3zm5.52 11l-.02-7.461h3V19zm-.02-8.23v-3h3v3zM16 19v-4.673h3V19zm0-5.442v-3h3v3z");
}

</style>

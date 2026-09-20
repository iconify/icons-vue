<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h180h9bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:skip-previous" /></template>
<style>
.h180h9bdr {
  fill: currentColor;
  d: path("M6.73 16.616V7.385h1v9.23zm10.54 0L10.345 12l6.923-4.615z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8kdavbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:smart-toy-sharp" /></template>
<style>
.z8kdavbox {
  fill: currentColor;
  d: path("M5 14q-.846 0-1.423-.577T3 12t.577-1.423T5 10V6h5q0-.846.577-1.423T12 4t1.423.577T14 6h5v4q.846 0 1.423.577T21 12t-.577 1.423T19 14v6H5zm4.707-1.791q.293-.291.293-.707t-.291-.709t-.707-.293t-.709.291t-.293.707t.291.709t.707.293t.709-.291m6 0q.293-.291.293-.707t-.291-.709t-.707-.293t-.709.291t-.293.707t.291.709t.707.293t.709-.291M8.5 16.5h7v-1h-7z");
}

</style>

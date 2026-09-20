<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1fb2mw3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tree-deciduous-24-filled" /></template>
<style>
.p1fb2mw3f {
  fill: currentColor;
  d: path("M7.998 4.816a4.251 4.251 0 0 1 8.004 0a4.25 4.25 0 0 1 3.364 5.247a4.25 4.25 0 0 1-1.687 7.915a.8.8 0 0 1-.179.022h-3v2.25A1.75 1.75 0 0 1 12.75 22h-1.5a1.75 1.75 0 0 1-1.75-1.75V18h-3a.8.8 0 0 1-.179-.021a4.25 4.25 0 0 1-1.687-7.916a4.256 4.256 0 0 1 3.364-5.247M11 18v2.25c0 .138.112.25.25.25h1.5a.25.25 0 0 0 .25-.25V18z");
}

</style>

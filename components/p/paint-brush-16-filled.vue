<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x-lcoibxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:paint-brush-16-filled" /></template>
<style>
.x-lcoibxd {
  fill: currentColor;
  d: path("M10 4.5V1H9v2.5a.5.5 0 0 1-1 0V1H3.5a.5.5 0 0 0-.5.5V7h10V1.5a.5.5 0 0 0-.5-.5H11v3.5a.5.5 0 0 1-1 0M13 8H3v1a2 2 0 0 0 2 2h1.5v2.5a1.5 1.5 0 0 0 3 0V11H11a2 2 0 0 0 2-2z");
}

</style>

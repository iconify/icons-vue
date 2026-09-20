<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g9co0bb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-text-multiple-16-regular" /></template>
<style>
.g9co0bb2r {
  fill: currentColor;
  d: path("M4.5 4a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zM4 6.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5M4.5 8a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zm-3-3.5A2.5 2.5 0 0 1 4 2h6.5A2.5 2.5 0 0 1 13 4.5v5a2.5 2.5 0 0 1-2.5 2.5H4a2.5 2.5 0 0 1-2.5-2.5zM4 3a1.5 1.5 0 0 0-1.5 1.5v5A1.5 1.5 0 0 0 4 11h6.5A1.5 1.5 0 0 0 12 9.5v-5A1.5 1.5 0 0 0 10.5 3zm10 6.5a3.5 3.5 0 0 1-3.5 3.5H3.671c.773.626 1.757 1 2.829 1h4A4.5 4.5 0 0 0 15 9.5v-3a4.48 4.48 0 0 0-1-2.829z");
}

</style>

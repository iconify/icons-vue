<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i86-grbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tablet-16-regular" /></template>
<style>
.i86-grbcj {
  fill: currentColor;
  d: path("M6.5 10a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zM2.75 3A1.75 1.75 0 0 0 1 4.75v6.5c0 .966.784 1.75 1.75 1.75h10.5A1.75 1.75 0 0 0 15 11.25v-6.5A1.75 1.75 0 0 0 13.25 3zM2 4.75A.75.75 0 0 1 2.75 4h10.5a.75.75 0 0 1 .75.75v6.5a.75.75 0 0 1-.75.75H2.75a.75.75 0 0 1-.75-.75z");
}

</style>

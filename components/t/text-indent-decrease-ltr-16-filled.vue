<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wlvy9xbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-indent-decrease-ltr-16-filled" /></template>
<style>
.wlvy9xbyf {
  fill: currentColor;
  d: path("M5.75 3a.75.75 0 0 0 0 1.5h5.5a.75.75 0 0 0 0-1.5zm0 4a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5zm0 4a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5zM2.72 5.72a.75.75 0 0 1 1.06 1.06l-.97.97l.97.97a.75.75 0 0 1-1.06 1.06l-1.5-1.5a.75.75 0 0 1 0-1.06z");
}

</style>

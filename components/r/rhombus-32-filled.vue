<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ghls6ybrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rhombus-32-filled" /></template>
<style>
.ghls6ybrc {
  fill: currentColor;
  d: path("M10.524 5a3.25 3.25 0 0 0-3.018 2.043l-6.2 15.5C.452 24.678 2.024 27 4.324 27h17.153a3.25 3.25 0 0 0 3.017-2.043l6.2-15.5C31.548 7.322 29.976 5 27.677 5z");
}

</style>

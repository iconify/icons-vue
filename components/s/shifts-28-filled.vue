<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="o7_qvbc-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shifts-28-filled" /></template>
<style>
.o7_qvbc-w {
  fill: currentColor;
  d: path("M3 6.25A3.25 3.25 0 0 1 6.25 3h15.5A3.25 3.25 0 0 1 25 6.25v15.5A3.25 3.25 0 0 1 21.75 25H6.25A3.25 3.25 0 0 1 3 21.75zm11.5 1.5a.75.75 0 0 0-1.5 0v7c0 .414.336.75.75.75h5.5a.75.75 0 0 0 0-1.5H14.5z");
}

</style>

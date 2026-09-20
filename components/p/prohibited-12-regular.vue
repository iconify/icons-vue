<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="b8s8cmmrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:prohibited-12-regular" /></template>
<style>
.b8s8cmmrd {
  fill: currentColor;
  d: path("M6 1a5 5 0 1 0 0 10A5 5 0 0 0 6 1M2 6a4 4 0 0 1 6.453-3.16L2.84 8.453A4 4 0 0 1 2 6m1.547 3.16L9.16 3.547A4 4 0 0 1 3.547 9.16");
}

</style>

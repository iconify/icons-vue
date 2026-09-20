<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o1txt7bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:notebook-section-20-regular" /></template>
<style>
.o1txt7bzx {
  fill: currentColor;
  d: path("M14 2.5a.5.5 0 0 0-1 0V3H8a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h5v.5a.5.5 0 0 0 1 0zM13 16H8a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h5z");
}

</style>

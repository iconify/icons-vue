<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_a00mb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:south" /></template>
<style>
.y_a00mb8o {
  fill: currentColor;
  d: path("m12 22l-7-7l1.4-1.4l4.6 4.575V2h2v16.175l4.6-4.6L19 15z");
}

</style>

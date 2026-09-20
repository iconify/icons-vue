<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="prppx356n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:oval-32-regular" /></template>
<style>
.prppx356n {
  fill: currentColor;
  d: path("M12 8a8 8 0 1 0 0 16h8a8 8 0 1 0 0-16zM2 16C2 10.477 6.477 6 12 6h8c5.523 0 10 4.477 10 10s-4.477 10-10 10h-8C6.477 26 2 21.523 2 16");
}

</style>

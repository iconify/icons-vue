<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j53nxlbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:molecule-32-filled" /></template>
<style>
.j53nxlbca {
  fill: currentColor;
  d: path("M22 16a7 7 0 1 0-6.406-4.174l-2.83 2.2a5.5 5.5 0 1 0-.269 7.252l4.776 2.68a4.5 4.5 0 1 0 1.09-1.682l-4.775-2.679A5.5 5.5 0 0 0 14 17.5c0-.59-.093-1.16-.266-1.694l2.929-2.277A6.99 6.99 0 0 0 22 16");
}

</style>

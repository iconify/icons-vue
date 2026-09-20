<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b268gdbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-cells-split-20-filled" /></template>
<style>
.b268gdbuf {
  fill: currentColor;
  d: path("M10 6h7v-.5A2.5 2.5 0 0 0 14.5 3H10zm7 7V7H3v6zm-7-5v4H9V8zm0 9h4.5a2.5 2.5 0 0 0 2.5-2.5V14h-7zm-1-3H3v.5A2.5 2.5 0 0 0 5.5 17H9zm0-8V3H5.5A2.5 2.5 0 0 0 3 5.5V6z");
}

</style>

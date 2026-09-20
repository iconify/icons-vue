<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="peuhpybvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:transparency-square-16-filled" /></template>
<style>
.peuhpybvs {
  fill: currentColor;
  d: path("M11.5 1.5a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3h-7a3 3 0 0 1-3-3v-7a3 3 0 0 1 3-3zM4.5 3A1.5 1.5 0 0 0 3 4.5v1h2.5V8H3v2.5h2.5V13H8v-2.5h2.5V13h1a1.5 1.5 0 0 0 1.5-1.5v-1h-2.5V8H13V5.5h-2.5V3H8v2.5H5.5V3zM8 10.5H5.5V8H8zM10.5 8H8V5.5h2.5z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xtsrj-edz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sleepa" /></template>
<style>
.xtsrj-edz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.18 34.32A21.493 21.493 0 0 1 15.454 4.275a21.498 21.498 0 1 0 28.271 28.27a21.4 21.4 0 0 1-8.545 1.775");
}

</style>

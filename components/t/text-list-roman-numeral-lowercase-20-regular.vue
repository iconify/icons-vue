<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yttk1ibla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-list-roman-numeral-lowercase-20-regular" /></template>
<style>
.yttk1ibla {
  fill: currentColor;
  d: path("M4.5 2a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m0 .5A.5.5 0 0 1 5 3v2.5a.5.5 0 0 1-1 0V3a.5.5 0 0 1 .5-.5m0 6A.5.5 0 0 1 5 9v2.5a.5.5 0 0 1-1 0V9a.5.5 0 0 1 .5-.5M5 15a.5.5 0 0 0-1 0v2.5a.5.5 0 0 0 1 0zM8 4.5a.5.5 0 0 1 .5-.5h8a.5.5 0 0 1 0 1h-8a.5.5 0 0 1-.5-.5m0 5a.5.5 0 0 1 .5-.5h8a.5.5 0 0 1 0 1h-8a.5.5 0 0 1-.5-.5m0 5a.5.5 0 0 1 .5-.5h8a.5.5 0 0 1 0 1h-8a.5.5 0 0 1-.5-.5m-3-7a.5.5 0 1 1-1 0a.5.5 0 0 1 1 0M4.5 14a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

</style>

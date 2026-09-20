<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sdw6rpb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:multiselect-16-regular" /></template>
<style>
.sdw6rpb-o {
  fill: currentColor;
  d: path("M4.854 2.146a.5.5 0 0 1 0 .708l-2 2a.5.5 0 0 1-.708 0l-1-1a.5.5 0 1 1 .708-.708l.646.647l1.646-1.647a.5.5 0 0 1 .708 0M14.5 4h-8a.5.5 0 0 1 0-1h8a.5.5 0 0 1 0 1M6 8a.5.5 0 0 1 .5-.5h8a.5.5 0 0 1 0 1h-8A.5.5 0 0 1 6 8m-1.146 3.146a.5.5 0 0 1 0 .708l-2 2a.5.5 0 0 1-.708 0l-1-1a.5.5 0 0 1 .708-.708l.646.647l1.646-1.647a.5.5 0 0 1 .708 0M14.5 13h-8a.5.5 0 0 1 0-1h8a.5.5 0 0 1 0 1");
}

</style>

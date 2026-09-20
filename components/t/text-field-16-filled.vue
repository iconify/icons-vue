<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a41exc0wf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-field-16-filled" /></template>
<style>
.a41exc0wf {
  fill: currentColor;
  d: path("M3.5 2A2.5 2.5 0 0 0 1 4.5v7A2.5 2.5 0 0 0 3.5 14h9a2.5 2.5 0 0 0 2.5-2.5v-7A2.5 2.5 0 0 0 12.5 2zM7 11h.5V5H5v.5a.5.5 0 0 1-1 0v-1a.5.5 0 0 1 .5-.5h7a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-1 0V5H8.5v6H9a.5.5 0 0 1 0 1H7a.5.5 0 0 1 0-1");
}

</style>

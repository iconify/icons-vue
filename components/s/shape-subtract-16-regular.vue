<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i7a-gs-ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shape-subtract-16-regular" /></template>
<style>
.i7a-gs-ye {
  fill: currentColor;
  d: path("M4 2a2 2 0 0 0-2 2v5a2 2 0 0 0 .01.204A2.004 2.004 0 0 0 4 11h1v1a2 2 0 0 0 2 2h5a2 2 0 0 0 2-2V7a2 2 0 0 0-2-2h-1V4a2 2 0 0 0-2-2zm1.143 1L3 5.143V4a1 1 0 0 1 1-1zM3 6.557L6.557 3h1.586L3 8.143zm6.45-3.45A1 1 0 0 1 10 4v.293L9.293 5H7.557zM5 7.557v1.736L4.293 10H4a1 1 0 0 1-.893-.55zM6 7a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1z");
}

</style>

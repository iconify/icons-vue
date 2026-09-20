<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="owirh2bni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:work-iq-16-filled" /></template>
<style>
.owirh2bni {
  fill: currentColor;
  d: path("M8 2a7 7 0 0 1 7 7a4 4 0 0 1-3 3.874V9.5A2.5 2.5 0 1 0 9.5 12a.5.5 0 0 0 0-1A1.5 1.5 0 1 1 11 9.5V13a2 2 0 0 0 2 2h.5a.5.5 0 0 1 0 1H13a3 3 0 0 1-3-3h-.5a3.5 3.5 0 0 1-2.448-1H4a3 3 0 0 1-3-3a7 7 0 0 1 7-7");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xy9zwmbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-key-16-regular" /></template>
<style>
.xy9zwmbbt {
  fill: currentColor;
  d: path("M12 6a3 3 0 1 1-1 5.83v.67a.5.5 0 0 1-.5.5H10v.5a.5.5 0 0 1-.5.5H9v.5a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1-.5-.5v-1.086a1 1 0 0 1 .293-.707l2.836-2.836A3 3 0 0 1 12 6M8.126 8Q8.002 8.481 8 9H3.5a.5.5 0 0 0-.5.5v.5c0 1.041.752 2.148 2.142 2.679a2 2 0 0 0-.142.735v.274C3.086 13.045 2 11.506 2 10v-.5A1.5 1.5 0 0 1 3.5 8zm4.624-.5a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5M7 1.5A2.75 2.75 0 1 1 7 7a2.75 2.75 0 0 1 0-5.5m0 1A1.75 1.75 0 1 0 7 6a1.75 1.75 0 0 0 0-3.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ft5dv1b6b"><path class="oep73yb1v"/><path class="hotr1lz7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:restore-16-filled" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hotr1lz7y {
  d: path("M4.5 5A1.5 1.5 0 0 0 3 6.5v5A1.5 1.5 0 0 0 4.5 13h5a1.5 1.5 0 0 0 1.5-1.5v-5A1.5 1.5 0 0 0 9.5 5h-5z");
  fill: currentColor;
}

.oep73yb1v {
  d: path("M5.085 4H10a2 2 0 0 1 2 2v4.915A1.5 1.5 0 0 0 13 9.5V6a3 3 0 0 0-3-3H6.5a1.5 1.5 0 0 0-1.415 1z");
  fill: currentColor;
}

</style>

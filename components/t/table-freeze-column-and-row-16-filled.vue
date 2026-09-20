<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="omrfalk4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-freeze-column-and-row-16-filled" /></template>
<style>
.omrfalk4d {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5v7A2.5 2.5 0 0 0 4.5 14H10v-3H6v2H4.5A1.5 1.5 0 0 1 3 11.5v-7A1.5 1.5 0 0 1 4.5 3h7A1.5 1.5 0 0 1 13 4.5V6h-2v4h3V4.5A2.5 2.5 0 0 0 11.5 2zM6 6v4h4V6zm5 5v3h.5a2.5 2.5 0 0 0 2.5-2.5V11z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rh2ou3bdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:select-all-off-16-regular" /></template>
<style>
.rh2ou3bdv {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5v5A2.5 2.5 0 0 0 4.5 12h5A2.5 2.5 0 0 0 12 9.5v-5A2.5 2.5 0 0 0 9.5 2zM3 4.5A1.5 1.5 0 0 1 4.5 3h5A1.5 1.5 0 0 1 11 4.5v5A1.5 1.5 0 0 1 9.5 11h-5A1.5 1.5 0 0 1 3 9.5zM5 13c.456.607 1.182 1 2 1h2.5A4.5 4.5 0 0 0 14 9.5V6c0-.818-.393-1.544-1-2v5.5A3.5 3.5 0 0 1 9.5 13z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee0uxubkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shades-outline" /></template>
<style>
.ee0uxubkm {
  fill: currentColor;
  d: path("M4 20.98V4H3V3h18v1h-1v17q-2.061 0-3.655-1.24t-1.954-3.26H9.584q-.368 2-1.958 3.24T4 20.98m1-1.072q1.58-.35 2.656-1.562Q8.73 17.135 8.73 15.5V4H5zM9.73 15.5h4.54V4H9.73zM19 19.889V4h-3.73v11.5q0 1.616 1.059 2.83q1.06 1.214 2.671 1.559M8.73 4H5zM19 4h-3.73z");
}

</style>

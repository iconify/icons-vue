<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iegqrq-iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-quilt-outline-rounded" /></template>
<style>
.iegqrq-iv {
  fill: currentColor;
  d: path("M4 16.385v-8.77q0-.666.497-1.14Q4.994 6 5.692 6h12.616q.698 0 1.195.475q.497.474.497 1.14v8.77q0 .666-.497 1.14q-.497.475-1.195.475H5.692q-.698 0-1.195-.475Q4 17.052 4 16.386M9.94 11.5H19V7.616q0-.231-.212-.424T18.309 7H9.94zm5.024 5.5h3.344q.269 0 .48-.192t.212-.424V12.5h-4.036zM9.94 17h4.022v-4.5h-4.02zm-4.249 0H8.94V7H5.692q-.269 0-.48.192T5 7.616v8.769q0 .23.212.423t.48.192");
}

</style>

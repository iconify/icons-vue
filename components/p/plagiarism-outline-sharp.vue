<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0s_8iolc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:plagiarism-outline-sharp" /></template>
<style>
.w0s_8iolc {
  fill: currentColor;
  d: path("M11.45 17q.45 0 .888-.112t.812-.338L15.6 19l1.4-1.4l-2.45-2.45q.225-.375.338-.812T15 13.45Q15 12 13.975 11T11.5 10t-2.475 1.025T8 13.5t1 2.475T11.45 17m-1.012-2.437Q10 14.125 10 13.5t.438-1.062T11.5 12t1.063.438T13 13.5t-.437 1.063T11.5 15t-1.062-.437M4 22V2h10l6 6v14zm9-13V4H6v16h12V9zM6 4v5zv16z");
}

</style>

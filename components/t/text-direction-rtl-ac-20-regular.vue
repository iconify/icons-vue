<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="nrspho85i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-rtl-ac-20-regular" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nrspho85i {
  d: path("M15 2.5a.5.5 0 0 0-1 0v8a.5.5 0 0 0 1 0V7h1.5a.5.5 0 0 0 0-1H15V2.5zM8.5 3a.5.5 0 0 0 0 1H12v.75c0 .948-.192 2.028-.721 2.855C10.769 8.401 9.928 9 8.5 9a.5.5 0 0 0 0 1c1.772 0 2.93-.776 3.621-1.855c.67-1.048.879-2.343.879-3.395V3.5a.5.5 0 0 0-.5-.5h-4zM5.146 4.146a.5.5 0 1 1 .708.708L4.707 6H6.5a.5.5 0 0 1 0 1H4.707l1.147 1.146a.5.5 0 1 1-.708.708l-2-2a.5.5 0 0 1 0-.708l2-2zm0 8a.5.5 0 0 1 .708.708L4.707 14H16.5a.5.5 0 0 1 0 1H4.707l1.147 1.146a.5.5 0 0 1-.708.708l-2-2a.5.5 0 0 1 0-.708l2-2z");
  fill: currentColor;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2mp-vi4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:xray-film" /></template>
<style>
.e2mp-vi4w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 5.25V3.5q0-1.75 1.75-1.75h12.5q1.75 0 1.75 1.75V16q0 1.75-1.75 1.75h-1.25v1.125q0 3.375-3.375 3.375H5.125q-3.375 0-3.375-3.375V8.625q0-3.375 3.375-3.375zm13 11V8.625q0-3.375-3.375-3.375H7.75V3.5q0-.25.25-.25h12.5q.25 0 .25.25V16q0 .25-.25.25zm-6.25-8q-2 0-2 2q0 1.095.599 1.59L8.34 15.099q-.495-.599-1.59-.599q-2 0-2 2q0 1.625 1.32 1.93q.305 1.32 1.93 1.32q2 0 2-2q0-1.095-.599-1.59l3.259-3.259q.495.599 1.59.599q.828 0 1.414-.586t.586-1.414t-.586-1.414q-.341-.342-.766-.484q-.142-.425-.484-.766Q13.828 8.25 13 8.25");
}

</style>

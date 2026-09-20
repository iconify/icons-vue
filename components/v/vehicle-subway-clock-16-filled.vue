<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k68mn5btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vehicle-subway-clock-16-filled" /></template>
<style>
.k68mn5btf {
  fill: currentColor;
  d: path("M9 4.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0M4.5 2a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 .5.5H6a.5.5 0 0 0 0-1H5V2.5a.5.5 0 0 0-.5-.5m0 8q.253 0 .5-.022V10a1 1 0 1 0 1.85-.526A5.5 5.5 0 0 0 8.744 8H13V4.5A1.5 1.5 0 0 0 11.5 3H9.793A5.5 5.5 0 0 0 9.4 2h2.1A2.5 2.5 0 0 1 14 4.5v6a2.5 2.5 0 0 1-2.5 2.5h-.617l1.865 1.066a.5.5 0 1 1-.496.868L8.867 13H7.133l-3.385 1.934a.5.5 0 0 1-.496-.868L5.117 13H4.5A2.5 2.5 0 0 1 2 10.5V9.4c.75.384 1.6.6 2.5.6m5.5 1a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>

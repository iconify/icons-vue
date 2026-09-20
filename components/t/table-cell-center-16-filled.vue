<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eln6d5dqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-cell-center-16-filled" /></template>
<style>
.eln6d5dqa {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5V5h3V2zM6 2v3h4V2zM5 6H2v4h3zm0 5H2v.5A2.5 2.5 0 0 0 4.5 14H5zm1 3h4v-3H6zm5 0v-3h3v.5a2.5 2.5 0 0 1-2.5 2.5zm3-8v4h-3V6zm0-1v-.5A2.5 2.5 0 0 0 11.5 2H11v3z");
}

</style>

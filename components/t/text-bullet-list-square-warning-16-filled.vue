<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j4z7i-bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-square-warning-16-filled" /></template>
<style>
.j4z7i-bho {
  fill: currentColor;
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2h7A2.5 2.5 0 0 1 14 4.5v4.02l-.707-1.414c-.738-1.475-2.843-1.475-3.58.001l-.196.393H7a.5.5 0 0 0 0 1h2.017l-.998 2H7a.5.5 0 0 0 0 1h.52L6.27 14H4.5A2.5 2.5 0 0 1 2 11.5zm3.5.5A.75.75 0 1 0 4 5a.75.75 0 0 0 1.5 0m0 3A.75.75 0 1 0 4 8a.75.75 0 0 0 1.5 0m-.75 3.75a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5M6.5 5a.5.5 0 0 0 .5.5h4.5a.5.5 0 0 0 0-1H7a.5.5 0 0 0-.5.5m4.103 2.554a1 1 0 0 1 1.79 0l3.5 6.998A1 1 0 0 1 14.998 16H8.002a1 1 0 0 1-.895-1.448zm1.395 1.941a.5.5 0 1 0-1 0v3.002a.5.5 0 1 0 1 0zm-.5 5.504a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

</style>

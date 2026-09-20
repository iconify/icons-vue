<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qqsgtklth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:temperature-48-filled" /></template>
<style>
.qqsgtklth {
  fill: currentColor;
  d: path("M24 9a3.75 3.75 0 0 0-3.75 3.75v15.207l-.484.445a6.25 6.25 0 1 0 8.467 0l-.483-.445V12.75A3.75 3.75 0 0 0 24 9m-6.75 3.75a6.75 6.75 0 0 1 13.5 0v13.925a9.25 9.25 0 1 1-13.5 0zM28 33a4 4 0 1 1-5.5-3.71V18.5a1.5 1.5 0 0 1 3 0v10.79A4 4 0 0 1 28 33");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ihih4mbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-left-add-16-regular" /></template>
<style>
.ihih4mbjl {
  fill: currentColor;
  d: path("M1 4.5A2.5 2.5 0 0 1 3.5 2h7A2.5 2.5 0 0 1 13 4.5v1.707a5.5 5.5 0 0 0-1-.185V4.5A1.5 1.5 0 0 0 10.5 3H6v8h.022a5.6 5.6 0 0 0 0 1H3.5A2.5 2.5 0 0 1 1 9.5zM5 3H3.5A1.5 1.5 0 0 0 2 4.5v5A1.5 1.5 0 0 0 3.5 11H5zm11 8.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4-2a.5.5 0 0 0-1 0V11H9.5a.5.5 0 0 0 0 1H11v1.5a.5.5 0 0 0 1 0V12h1.5a.5.5 0 0 0 0-1H12z");
}

</style>

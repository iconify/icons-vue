<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dd9hwbbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tag-add-16-regular" /></template>
<style>
.dd9hwbbgr {
  fill: currentColor;
  d: path("M10 5a1 1 0 1 1 0-2a1 1 0 0 1 0 2M1.587 9.136a1.99 1.99 0 0 1 0-2.822l4.74-4.716a2 2 0 0 1 1.41-.584L10.986 1A2 2 0 0 1 13 3.01l-.019 2.58a5.5 5.5 0 0 0-1-.388l.017-2.2a1 1 0 0 0-1.007-1.004l-3.25.013a1 1 0 0 0-.705.292L2.296 7.02a.994.994 0 0 0 0 1.41l2.743 2.73c.071.596.238 1.163.484 1.684a2 2 0 0 1-.64-.428zM15 10.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4-2a.5.5 0 0 0-1 0V10H8.5a.5.5 0 0 0 0 1H10v1.5a.5.5 0 0 0 1 0V11h1.5a.5.5 0 0 0 0-1H11z");
}

</style>

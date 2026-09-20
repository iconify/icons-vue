<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ft5dv1b6b"><path class="v28kpgctu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-right-expand-16-regular" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.v28kpgctu {
  d: path("M9.707 8.5l.647.646a.5.5 0 0 1-.708.708l-1.5-1.5a.5.5 0 0 1 0-.708l1.5-1.5a.5.5 0 0 1 .708.708l-.647.646h1.791a.5.5 0 0 1 0 1h-1.79zM4 2.999a2 2 0 0 0-2 2V11a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2H4zm-1 2a1 1 0 0 1 1-1h2.002V12H4a1 1 0 0 1-1-1V5zM7.002 12V4H12a1 1 0 0 1 1 1V11a1 1 0 0 1-1 1H7.002z");
  fill: currentColor;
}

</style>

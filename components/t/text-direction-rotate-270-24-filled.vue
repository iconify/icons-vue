<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f46-klg7a"/><path class="c0ikd4l8m"/><path class="oe0t26bsk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-rotate-270-24-filled" /></template>
<style>
.c0ikd4l8m {
  d: path("M3.615 17.173l9 3.75a1 1 0 1 0 .77-1.846L11 18.084v-3.667l2.385-.994a1 1 0 0 0-.77-1.846l-9 3.75a1 1 0 0 0 0 1.846zM9 17.25l-2.4-1l2.4-1v2z");
  fill: currentColor;
}

.f46-klg7a {
  d: path("M19.707 5.293a1 1 0 1 1-1.414 1.414L18 6.414V20a1 1 0 1 1-2 0V6.414l-.293.293a1 1 0 0 1-1.414-1.414l2-2a1 1 0 0 1 1.414 0l2 2z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.oe0t26bsk {
  d: path("M10.707 6.707a1 1 0 0 0 0-1.414l-2-2a1 1 0 0 0-1.414 0l-2 2a1 1 0 1 0 1.414 1.414L7 6.414V10a1 1 0 1 0 2 0V6.414l.293.293a1 1 0 0 0 1.414 0z");
  fill: currentColor;
}

</style>

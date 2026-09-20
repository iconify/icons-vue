<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rvs_olkjp"/><path class="wi4m5-79r"/><path class="pkypaobnt"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:projectm" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.pkypaobnt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.181 13.688v5.417a1.81 1.81 0 0 1-1.805 1.805c-.452 0-.903-.18-1.264-.541m16.361-6.681h1.896m-.903-1.534v6.319m-23.78-4.785v4.785m0-2.979a1.81 1.81 0 0 1 1.805-1.806m3.712 4.785za1.81 1.81 0 0 1-1.806-1.805v-1.174a1.81 1.81 0 0 1 1.806-1.806a1.81 1.81 0 0 1 1.805 1.806v1.174a1.81 1.81 0 0 1-1.805 1.805m-2.459 18.755V24.717L24 37.228l6.256-12.511v12.511");
}

.rvs_olkjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.631 13.688v7.222m-.001-4.243a1.81 1.81 0 0 0 1.806 1.806a1.81 1.81 0 0 0 1.806-1.806v-1.173a1.81 1.81 0 0 0-1.806-1.806a1.81 1.81 0 0 0-1.805 1.806M35.59 17.57c-.27.542-.902.903-1.534.903a1.81 1.81 0 0 1-1.806-1.805v-1.174a1.81 1.81 0 0 1 1.806-1.806c.632 0 1.264.361 1.534.903m-5.833 2.979c-.271.542-.903.903-1.535.903a1.81 1.81 0 0 1-1.805-1.805v-1.174a1.81 1.81 0 0 1 1.805-1.806a1.81 1.81 0 0 1 1.806 1.806v.632h-3.612");
}

.wi4m5-79r {
  fill: currentColor;
  d: path("M24.931 11.522a.75.75 0 0 1-1.5 0a.75.75 0 0 1 1.5 0");
}

</style>

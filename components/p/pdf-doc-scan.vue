<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fnp3t08vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pdf-doc-scan" /></template>
<style>
.fnp3t08vd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33 42.5h5.5a4 4 0 0 0 4-4v-4.084m-37 2V38.5a4 4 0 0 0 4 4h7.688m0-37H9.5a4 4 0 0 0-4 4v3.172M30.813 5.5H38.5a4 4 0 0 1 4 4v3.172m.778 2.675L22.832 3.541a1.75 1.75 0 0 0-2.389.64l-15.3 26.508a1.75 1.75 0 0 0 .64 2.39h0l20.445 11.806a1.75 1.75 0 0 0 2.39-.64l15.301-26.508a1.75 1.75 0 0 0-.64-2.39m-9.028 3.831l-13.52-7.919m15.275 13.333l-17.233-9.95m15.249 13.403L16.79 18.094");
}

</style>

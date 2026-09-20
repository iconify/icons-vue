<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ft5dv1b6b"><path class="mr-p7xb4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:signed-16-filled" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mr-p7xb4u {
  d: path("M11.335 2.065l.077.153l.576 1.533c.045.12.14.216.261.261l1.48.556c.65.243.999.937.826 1.594l-.042.13l-.688 1.523a.447.447 0 0 0 0 .37l.654 1.44a1.34 1.34 0 0 1-.544 1.71l-.153.077l-1.533.576a.446.446 0 0 0-.26.261l-.556 1.48a1.34 1.34 0 0 1-1.595.826l-.13-.042l-1.523-.688a.447.447 0 0 0-.37 0l-1.439.654a1.34 1.34 0 0 1-1.71-.544l-.077-.153l-.577-1.533a.446.446 0 0 0-.261-.26l-1.48-.556a1.34 1.34 0 0 1-.826-1.595l.042-.13l.689-1.523a.447.447 0 0 0 0-.37l-.654-1.439a1.34 1.34 0 0 1 .543-1.71l.153-.077l1.533-.577a.447.447 0 0 0 .261-.261l.556-1.48a1.34 1.34 0 0 1 1.594-.826l.13.042l1.523.689a.447.447 0 0 0 .37 0l1.44-.654a1.34 1.34 0 0 1 1.71.543zm-1.17 3.641l-3.187 3.64l-1.162-1.162a.447.447 0 1 0-.632.632l1.5 1.5a.447.447 0 0 0 .652-.022l3.5-4a.447.447 0 0 0-.672-.588z");
  fill: currentColor;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k7-yw7ceq"/><path class="n6xqvubeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:react" /></template>
<style>
.k7-yw7ceq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.44 24.76c21.734 0 11.732 18.335 23.027 18.335c3.876 0 5.24-2.934 5.24-2.934M11.44 4.5v39");
}

.n6xqvubeo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.293 4.5h16.011c6.054 0 10.96 4.535 10.96 10.13q0 0 0 0c0 5.594-4.906 10.13-10.96 10.13H11.46M8.293 43.5h6.293");
}

</style>

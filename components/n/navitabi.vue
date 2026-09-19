<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t2bq34u5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:navitabi" /></template>
<style>
.t2bq34u5h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.399 38.703L17.34 9.296a.665.665 0 0 0-1.245 0L5.036 38.703a.59.59 0 0 0 .868.704l8.577-5.473a4.16 4.16 0 0 1 4.473 0l8.576 5.473a.59.59 0 0 0 .869-.704M19.601 9.297L30.66 38.704a.665.665 0 0 0 1.245 0L42.964 9.295a.59.59 0 0 0-.868-.704l-8.577 5.473a4.16 4.16 0 0 1-4.473 0L20.47 8.592a.59.59 0 0 0-.869.704z");
}

</style>

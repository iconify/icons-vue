<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dv_8afwqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:notewise" /></template>
<style>
.dv_8afwqc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.672 12.328l6.828 6.828l-23.216 23.216L5.5 42.5l.128-13.784L28.844 5.5");
}

</style>

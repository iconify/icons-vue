<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dyx4j9bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wazirx" /></template>
<style>
.dyx4j9bay {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.669 36.444L43.5 13.81L14.612 36.044m-8.225 0L24 5.882m-8.884 15.215L4.5 13.447l1.887 22.597m35.282.4v5.674m0 0H6.402m-.015-6.074v6.022m0-6.022h35.138M33.24 21.706L24 5.882");
}

</style>

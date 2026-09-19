<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wd7y3rbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oxygenupdater" /></template>
<style>
.wd7y3rbyi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.945 42.5h36.11M9.19 22.599h7.063v14.224a2.02 2.02 0 0 0 2.022 2.021H29.77a2.02 2.02 0 0 0 2.021-2.021V22.599h7.064a.95.95 0 0 0 .706-1.689L25.435 6.018a2.004 2.004 0 0 0-2.688 0L8.483 20.91c-.755.789-.473 1.688.706 1.688Z");
}

</style>

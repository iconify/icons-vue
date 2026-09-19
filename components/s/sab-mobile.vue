<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wscgdub1g"/><path class="oqesmhnro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sab-mobile" /></template>
<style>
.oqesmhnro {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m3.5 24l10.25 10.25l20.5-20.5L44.5 24L34.25 34.25l-20.5-20.5z");
}

.wscgdub1g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.75 13.75h20.5v20.5h-20.5z");
}

</style>

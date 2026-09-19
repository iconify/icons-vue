<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nfk_92b-o"/><path class="pmfu13fck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vivid-seats" /></template>
<style>
.nfk_92b-o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 7.979L24 40.02L42.5 7.979z");
}

.pmfu13fck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.5 7.979l-30.833 10.68h24.667M30.167 29.34l-18.5-10.681");
}

</style>

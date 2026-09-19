<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yjm1qhb_m"/><path class="w6984xbid"/><path class="azxpwkh4z"/><path class="xqhsnz7-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:phoneprofilesplus" /></template>
<style>
.azxpwkh4z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.16 33.395a2 2 0 0 1-2 2h-8.32a2 2 0 0 1-2-2v-18.79a2 2 0 0 1 2-2h8.32a2 2 0 0 1 2 2zM9.84 16.225h12.32m3.68-.5h12.32m-12.32 5.5h12.32m-12.32 5.5h12.32m-12.32 5.5h12.32m-28.32-1.54h12.32");
}

.w6984xbid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16 32.545a.75.75 0 1 0 .75.75a.74.74 0 0 0-.73-.75z");
}

.xqhsnz7-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.109 18.75l-4.218 5.2h4.218l-3.912 4.21");
}

.yjm1qhb_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 35.5v-23a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v23a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4");
}

</style>

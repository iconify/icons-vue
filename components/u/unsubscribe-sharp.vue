<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va__cdfvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:unsubscribe-sharp" /></template>
<style>
.va__cdfvo {
  fill: currentColor;
  d: path("m12 13l8-5V6l-8 5l-8-5v2zm3.463 8.538Q14 20.075 14 18t1.463-3.537T19 13t3.538 1.463T24 18t-1.463 3.538T19 23t-3.537-1.463M16 18.5h6v-1h-6zM2 20V4h20v7.7q-.7-.35-1.45-.525T19 11q-2.925 0-4.962 2.037T12 18q0 .5.075 1t.225 1z");
}

</style>

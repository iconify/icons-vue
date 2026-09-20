<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwasod7bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:step-out-sharp" /></template>
<style>
.nwasod7bm {
  fill: currentColor;
  d: path("M9.875 21.125Q9 20.25 9 19t.875-2.125T12 16t2.125.875T15 19t-.875 2.125T12 22t-2.125-.875M11 14V5.825L8.4 8.4L7 7l5-5l5 5l-1.425 1.4L13 5.825V14z");
}

</style>

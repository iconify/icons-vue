<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxudoacuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:takeout-dining-2-outline-rounded" /></template>
<style>
.sxudoacuv {
  fill: currentColor;
  d: path("M5.14 21q-.384 0-.636-.31q-.252-.311-.146-.69L7.8 6.135l-.05-.7q-.044-.599-.421-1.017T6.369 4t-.976.398T5 5.385v.942q0 .213-.144.356t-.357.144t-.356-.144T4 6.327v-.943q0-.993.696-1.689T6.385 3h10.377q.946 0 1.626.647q.68.646.739 1.601l.823 14.894q.025.348-.22.603t-.588.255zm.306-1h3.21L8.008 9.439zm4.216 0h9.296l-.831-14.684q-.034-.554-.427-.935T16.762 4H8.229q.254.308.375.67t.146.753zm4.337-2.943q.174-.174.174-.422v-3.231q.496-.131.835-.551t.338-.968V9.092q0-.156-.121-.277t-.283-.122t-.273.121t-.111.283v2.563h-.596V9.093q0-.157-.112-.278q-.111-.122-.273-.122t-.273.122t-.112.282v2.564h-.596V9.092q0-.157-.111-.278q-.112-.122-.273-.122t-.273.122t-.112.282v2.791q0 .547.329.967t.844.55v3.25q0 .25.163.413q.163.164.413.164t.423-.174M9.662 20h9.296z");
}

</style>

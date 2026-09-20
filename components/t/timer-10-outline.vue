<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td_fv_ppk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:timer-10-outline" /></template>
<style>
.td_fv_ppk {
  fill: currentColor;
  d: path("M14 16h3V8h-3zm0 3q-1.25 0-2.125-.875T11 16V8q0-1.25.875-2.125T14 5h3q1.25 0 2.125.875T20 8v8q0 1.25-.875 2.125T17 19zm-8 0V8H4V5h5v14z");
}

</style>

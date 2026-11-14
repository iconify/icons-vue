<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3b6t9pyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-running-track" /></template>
<style>
.m3b6t9pyd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.52 22.076q-.317-.264-1.031-.845Q2.75 14.929 2.75 11q.001-3.831 2.71-6.539T12 1.753t6.54 2.708T21.25 11q0 3.929-7.739 10.231q-.714.581-1.031.845q-.05.042-.107.074q-.056.033-.118.055t-.125.034q-.065.011-.13.011t-.13-.011q-.064-.012-.125-.034q-.062-.022-.118-.055q-.057-.032-.107-.074M13.75 6.75h-3.5q-1.76 0-3.005 1.245T6 11t1.245 3.005t3.005 1.245h3.5q1.76 0 3.005-1.245T18 11t-1.245-3.005T13.75 6.75");
}

</style>

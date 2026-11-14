<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppa56wb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:virtual-joystick" /></template>
<style>
.ppa56wb4m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 6q0-1.76 1.245-3.005T12 1.75t3.005 1.245T16.25 6t-1.245 3.005q-.971.971-2.255 1.185v2.071q3.608.103 6.259 1.219Q22.25 14.845 22.25 17t-3.241 3.52Q16.086 21.75 12 21.75t-7.009-1.23Q1.75 19.155 1.75 17t3.241-3.52q2.651-1.116 6.259-1.219V10.19q-1.284-.214-2.255-1.185Q7.75 7.76 7.75 6");
}

</style>

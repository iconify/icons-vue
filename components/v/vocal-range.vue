<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h0xyghbij"/><path class="vvw_xknqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vocal-range" /></template>
<style>
.h0xyghbij {
  d: path("M7.5 2.5h4a1 1 0 0 1 1 1V13a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V3.5a1 1 0 0 1 1-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vvw_xknqp {
  d: path("M3 11q0 .16.008.319t.023.318t.039.317t.055.314q.031.157.07.311q.039.155.085.308t.1.303t.115.297t.129.292t.144.285t.157.278t.17.269q.089.133.184.261t.196.252q.102.123.209.241t.22.231t.231.22t.241.209t.252.196t.261.184q.132.088.269.17t.278.157t.285.144t.292.129t.297.115t.303.1t.308.085t.311.07t.314.055q.158.023.317.039q.159.015.318.023t.319.008q.262 0 .522-.021q.261-.021.519-.063t.512-.104t.502-.145t.489-.185q.24-.103.472-.224t.453-.261t.43-.296q.21-.157.405-.331q.196-.173.378-.361q.181-.188.347-.391q.166-.202.315-.417q.148-.215.28-.441q.131-.227.243-.463q.113-.236.206-.48t.167-.495m.1-.39Q16 11.725 16 11m-6.5 6.5v4m6.75-4l2.25-2.25l2.25 2.25m-2.25-2.25v6.5m-2.25-2.25l2.25 2.25l2.25-2.25");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upsi5kjsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-wifi-pro-outline-rounded" /></template>
<style>
.upsi5kjsp {
  fill: currentColor;
  d: path("M12.707 16.207Q13 15.913 13 15.5t-.293-.707T12 14.5t-.707.293T11 15.5t.293.707t.707.293t.707-.293M9 21q-1.598 0-2.58-.952q-.984-.952-1.518-2.336q-.535-1.39-.718-2.933Q4 13.237 4 12.025q0-2.242.349-3.922t1.259-2.82q.91-1.154 2.442-1.719Q9.583 3 12 3t3.95.565t2.442 1.718q.91 1.14 1.259 2.82T20 12.025q0 1.212-.184 2.754q-.183 1.542-.718 2.933q-.534 1.384-1.517 2.336T15 21zm-.025-1h6q1.292 0 2.077-.894q.785-.895 1.21-2.17t.56-2.627q.134-1.353.134-2.284q0-2.029-.27-3.532q-.269-1.502-1.044-2.497q-.788-1.013-2.141-1.505Q14.148 4 11.975 4t-3.526.491t-2.141 1.505q-.775.994-1.044 2.497q-.27 1.503-.27 3.532q0 .93.135 2.284t.56 2.628t1.209 2.169Q7.683 20 8.975 20m3-8");
}

</style>

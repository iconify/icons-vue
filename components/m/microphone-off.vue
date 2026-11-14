<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvot11loq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:microphone-off" /></template>
<style>
.pvot11loq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 5.043V3.5q0-.098.019-.195t.057-.188t.093-.173t.124-.151t.151-.124t.173-.093t.188-.057T10 2.5h4q.098 0 .195.019t.188.057t.173.093q.081.054.151.124t.124.151q.055.082.093.173t.057.188T15 3.5v7.586M10.028 14H10q-.098 0-.195-.019t-.188-.057t-.173-.093t-.151-.124t-.124-.151t-.093-.173t-.057-.188T9 13v-.057M5.5 11q0 .16.008.319t.023.318q.016.159.039.317q.024.158.055.314q.031.157.07.311q.039.155.085.308t.1.303t.115.297t.129.292t.144.285q.075.141.157.278t.17.269q.089.133.184.261t.196.252q.102.123.209.241t.22.231t.231.22t.241.209t.252.196t.261.184q.132.088.269.17t.278.157t.285.144t.292.129t.297.115t.303.1t.308.085t.311.07t.314.055q.158.023.317.039q.159.015.318.023T12 17.5q.7 0 1.384-.149m4.442-3.469q.333-.672.503-1.402q.171-.73.171-1.48M12 17.5v4m-8.5-18l17 17");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccb5lxbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:microphone-off" /></template>
<style>
.ccb5lxbfo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.027 5.1q.018-.134.048-.265q.03-.132.071-.26q.042-.128.095-.252t.116-.243t.138-.231q.075-.113.159-.218q.084-.106.177-.203t.194-.186t.211-.168t.224-.149q.116-.069.238-.128t.247-.105q.126-.048.256-.084t.263-.06t.267-.036T12 2.5q.147 0 .294.014t.291.044q.145.028.286.071t.277.099t.266.126t.253.152t.236.175t.218.198t.198.218t.175.236t.152.253t.126.266t.099.277t.071.286q.029.144.044.291T15 5.5V11l-.002.1M5.5 11q0 .16.008.319t.023.318q.016.159.039.317q.024.158.055.314q.031.157.07.311q.039.155.085.308t.1.303t.115.297t.129.292t.144.285q.075.141.157.278t.17.269q.089.133.184.261t.196.252q.102.123.209.241t.22.231t.231.22t.241.209t.252.196t.261.184q.132.088.269.17t.278.157t.285.144t.292.129t.297.115t.303.1t.308.085t.311.07t.314.055q.158.023.317.039q.159.015.318.023T12 17.5q.7 0 1.384-.149m4.442-3.469q.333-.672.503-1.402q.171-.73.171-1.48M12 17.5v4m-8.5-18l17 17");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn-32uthy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:weather-snowy" /></template>
<style>
.fn-32uthy {
  fill: currentColor;
  d: path("M5.92 18.33q-.247-.247-.247-.58t.247-.58t.58-.247t.58.247t.247.58t-.247.58t-.58.247t-.58-.247m3 3q-.247-.247-.247-.58t.247-.58t.58-.247t.58.247t.247.58t-.247.58t-.58.247t-.58-.247m3-3q-.247-.247-.247-.58t.247-.58t.58-.247t.58.247t.247.58t-.247.58t-.58.247t-.58-.247m6 0q-.247-.247-.247-.58t.247-.58t.58-.247t.58.247t.247.58t-.247.58t-.58.247t-.58-.247m-3 3q-.247-.247-.247-.58t.247-.58t.58-.247t.58.247t.247.58t-.247.58t-.58.247t-.58-.247M7.5 14.5q-2.083 0-3.541-1.459Q2.5 11.583 2.5 9.5q0-1.94 1.308-3.356t3.275-1.633q.742-1.405 2.033-2.208Q10.408 1.5 12 1.5q2.154 0 3.701 1.428t1.801 3.559q1.84.111 2.92 1.28Q21.5 8.937 21.5 10.5q0 1.664-1.168 2.832T17.5 14.5z");
}

</style>

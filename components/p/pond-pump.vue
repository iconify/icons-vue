<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw2j6fa1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pond-pump" /></template>
<style>
.lw2j6fa1t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 9v3.25H6.5q-1.968 0-3.359 1.391T1.75 17t1.391 3.359T6.5 21.75H11q1.968 0 3.359-1.391T15.75 17t-1.391-3.359T11 12.25H9.5V9q0-5.25 5-5.25q4.25 0 4.25 5.25q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T20.25 9q0-6.75-5.75-6.75q-2.811 0-4.624 1.813Q8 5.939 8 9m12.076 2.52Q22 13.828 22 15.5q0 2.5-2.5 2.5T17 15.5q0-1.672 1.924-3.98q.047-.057.105-.103q.057-.047.122-.081q.066-.034.137-.055t.144-.028q.074-.007.147.001q.074.008.144.03q.071.022.136.057q.064.036.121.083q.053.043.096.096");
}

</style>

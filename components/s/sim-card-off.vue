<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztq2iwbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sim-card-off" /></template>
<style>
.ztq2iwbsz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.75 12.625v1.297l3 3V8.45q0-1.76-1.245-3.005l-2.45-2.45Q14.81 1.75 13.05 1.75H8.5q-1.643 0-2.837 1.084l6.415 6.416h1.297q3.375 0 3.375 3.375M4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094M15.5 22.25q1.643 0 2.837-1.084l-2.603-2.604q-.836.688-2.359.688h-2.75q-3.375 0-3.375-3.375v-3.25q0-1.273.48-2.066L4.25 7.078V18q0 1.76 1.245 3.005T8.5 22.25z");
}

</style>

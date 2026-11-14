<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aj36p1b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:routine-run" /></template>
<style>
.aj36p1b6p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.128 3.878q-.601.601-.79 1.372h-1.392Q14.598 3 12 3q-1.5 0-2.25.75q-.549.549-.696 1.5H7.696Q7.348 3 4.75 3q-1.5 0-2.25.75T1.75 6q0 3 3 3q2.598 0 2.946-2.25h1.358Q9.402 9 12 9t2.946-2.25h1.392q.189.771.79 1.372q.879.88 2.122.88t2.122-.88q.879-.879.878-2.123q.001-1.242-.878-2.121q-.879-.88-2.122-.88t-2.122.88m-1.735 8.983l6.5 4q.063.039.117.089t.098.11t.074.127t.048.139t.019.146q.003.074-.008.147q-.012.073-.038.142t-.064.132q-.094.152-.246.246l-6.5 4q-.063.038-.132.064t-.142.038q-.073.011-.147.008t-.146-.019q-.072-.018-.139-.048t-.127-.074t-.11-.098t-.089-.117q-.111-.181-.111-.393v-8q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q.212 0 .393.111m4.676 4.639l-4.319-2.658v5.316z");
}

</style>

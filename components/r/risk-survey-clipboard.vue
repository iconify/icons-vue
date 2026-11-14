<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwnpcib3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:risk-survey-clipboard" /></template>
<style>
.mwnpcib3v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.757 4.25H6.5Q3.75 4.25 3.75 7v12q0 2.75 2.75 2.75h11q2.75 0 2.75-2.75V7q0-2.75-2.75-2.75h-1.262q-.078-.772-.647-1.341Q14.932 2.25 14 2.25h-.75q1.243 0 2.121.879q.879.878.879 2.121q0 3-3 3h-2.5q-3 0-3-3q0-1.243.879-2.121q.878-.879 2.121-.879H10q-2.121 0-2.243 2m1.932-.061q.44-.439 1.061-.439h2.5q.621 0 1.061.439q.439.44.439 1.061q0 1.5-1.5 1.5h-2.5q-1.5 0-1.5-1.5q0-.621.439-1.061M11.5 11q1.45 0 2.475 1.025T15 14.5q0 1.059-.547 1.892l1.577 1.578q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163l-1.578-1.577Q12.559 18 11.5 18Q8 18 8 14.5t3.5-3.5");
}

</style>

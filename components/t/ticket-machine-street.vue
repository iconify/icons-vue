<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urnmxejay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ticket-machine-street" /></template>
<style>
.urnmxejay {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 1.75h7q1.76 0 3.005 1.245T19.75 6v8q0 1.76-1.245 3.005T15.5 18.25h-1V16q0-1.45-1.025-2.475T11 12.5H9q-3.5 0-3.5 3.5v1.01l-.005-.005Q4.25 15.76 4.25 14V6q0-1.76 1.245-3.005T8.5 1.75m5.75 3h-4.5q-2.5 0-2.5 2.5v1.5q0 2.5 2.5 2.5h4.5q2.5 0 2.5-2.5v-1.5q0-2.5-2.5-2.5m2.5 10.75V13q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 12.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v2.5q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146M9 13.75h2q.932 0 1.591.659T13.25 16v4q0 .932-.659 1.591T11 22.25H9q-2.25 0-2.25-2.25v-4q0-2.25 2.25-2.25m0 1.5q-.75 0-.75.75v4q0 .75.75.75h2q.75 0 .75-.75v-4q0-.75-.75-.75zm1.5 1.25v1.75h-1V16.5z");
}

</style>

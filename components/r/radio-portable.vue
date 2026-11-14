<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgvwfeljb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:radio-portable" /></template>
<style>
.vgvwfeljb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.75 7.25H18q1.76 0 3.005 1.245T22.25 11.5V17q0 1.76-1.245 3.005T18 21.25H6q-1.76 0-3.005-1.245T1.75 17v-5.5q0-1.76 1.245-3.005T6 7.25h.25V5.5q0-2.25 2.25-2.25h7q2.25 0 2.25 2.25zm-10 0V5.5q0-.75.75-.75h7q.75 0 .75.75v1.75zm.75 3q-4 0-4 4t4 4q1.657 0 2.828-1.172Q12.5 15.907 12.5 14.25t-1.172-2.828Q10.157 10.25 8.5 10.25m6 .5h4q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014m-6 6q-2.5 0-2.5-2.5t2.5-2.5q1.036 0 1.768.732T11 14.25q0 2.5-2.5 2.5m5.75-.5q0 2.25 2.25 2.25t2.25-2.25T16.5 14t-2.25 2.25");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j24evntjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:notification-badge" /></template>
<style>
.j24evntjp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 2.25h1q1.346 0 2.298.952T22.25 5.5q0 3.25-3.25 3.25h-1q-3.25 0-3.25-3.25T18 2.25m-11 2h5.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043q-.072-.014-.146-.014H7q-1.76 0-3.005 1.245T2.75 7v10q0 1.76 1.245 3.005T7 21.25h10q1.76 0 3.005-1.245T21.25 17v-6q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v6q0 2.75-2.75 2.75H7q-2.75 0-2.75-2.75V7q0-1.139.805-1.945Q5.861 4.25 7 4.25");
}

</style>

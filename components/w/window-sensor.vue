<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixf729b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:window-sensor" /></template>
<style>
.ixf729b3e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 1.75H6q-1.76 0-3.005 1.245T1.75 6v12q0 1.76 1.245 3.005T6 22.25h12q1.76 0 3.005-1.245T22.25 18V6q0-1.76-1.245-3.005T18 1.75zm0 0q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v19q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-19q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m6.25 4q2.5 0 2.5 2.5v.5q0 2.5-2.5 2.5h-.5q-2.5 0-2.5-2.5v-.5q0-2.5 2.5-2.5zm-.5 7h.5q2.5 0 2.5 2.5v.5q0 2.5-2.5 2.5h-.5q-2.5 0-2.5-2.5v-.5q0-2.5 2.5-2.5");
}

</style>

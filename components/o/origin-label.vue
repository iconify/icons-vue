<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw2qt6-ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:origin-label" /></template>
<style>
.pw2qt6-ey {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 4.25H6q-1.76 0-3.005 1.245T1.75 8.5v7q0 1.76 1.245 3.005T6 19.75h12q1.76 0 3.005-1.245T22.25 15.5v-7q0-1.76-1.245-3.005T18 4.25M5.26 7q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141q.014.072.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.01q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T4.5 7.75t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T5.25 7zm6.21 10.28q-3.72-3.719-3.72-6.03q0-1.76 1.245-3.005T12 7t3.005 1.245t1.245 3.005q0 2.311-3.72 6.03q-.052.053-.113.094t-.13.069t-.141.043T12 17.5t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094");
}

</style>

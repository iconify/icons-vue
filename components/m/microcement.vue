<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-la95ync"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:microcement" /></template>
<style>
.e-la95ync {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.25 3.25h-5.5q-2.5 0-2.5 2.5q0 1.036.732 1.768q.549.548 1.268.686v3.546H4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h16q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 11.75h-7.25v-3.5h4.5q1.036 0 1.768-.732t.732-1.768q0-2.5-2.5-2.5M4.875 14.5h14.25q3.125 0 3.125 3.125t-3.125 3.125H4.875q-1.294 0-2.21-.915q-.915-.916-.915-2.21t.915-2.21q.916-.915 2.21-.915");
}

</style>

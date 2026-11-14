<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upsnz9bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mobile-emulator" /></template>
<style>
.upsnz9bbp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 1.75h13q1.76 0 3.005 1.245T22.75 6v7.5q0 1.76-1.245 3.005T18.5 17.75h-5.75v2.5H16q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.25 21q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T8 20.25h3.25v-2.5H5.5q-1.76 0-3.005-1.245T1.25 13.5V6q0-1.76 1.245-3.005T5.5 1.75m8 2.75h-3q-1.036 0-1.768.732T8 7v5.5q0 1.036.732 1.768T10.5 15h3q1.036 0 1.768-.732T16 12.5V7q0-2.5-2.5-2.5");
}

</style>

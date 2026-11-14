<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9u2x5f0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:two-factor-app" /></template>
<style>
.p9u2x5f0l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.5 1.25h-5q-1.76 0-3.005 1.245T5.25 5.5v13q0 1.76 1.245 3.005T9.5 22.75h5q1.76 0 3.005-1.245T18.75 18.5v-13q0-1.76-1.245-3.005T14.5 1.25M13.5 4q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T10.5 4zM11 10.75V9.5q0-1 1-1q.414 0 .707.293T13 9.5v1.25zm3.5.127q1.5.437 1.5 2.373v2q0 2.5-2.5 2.5h-3q-1.036 0-1.768-.732T8 15.25v-2q0-1.036.732-1.768q.35-.349.768-.532V9.5Q9.5 7 12 7q1.036 0 1.768.732T14.5 9.5z");
}

</style>

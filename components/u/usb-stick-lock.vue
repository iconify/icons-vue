<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fco155fad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:usb-stick-lock" /></template>
<style>
.fco155fad {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.75 1.75h-3.5q-2.5 0-2.5 2.5v3q0 .913.569 1.591q-.437.266-.824.654Q6.25 10.74 6.25 12.5V18q0 1.76 1.245 3.005T10.5 22.25h3q1.76 0 3.005-1.245T17.75 18v-5.5q0-1.76-1.245-3.005q-.387-.388-.824-.654q.569-.678.569-1.591v-3q0-1.036-.732-1.768T13.75 1.75M13.25 5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T10 5.75t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T10.75 5zm-1.75 8.75v-.25q0-.5.5-.5t.5.5v.25zM14 14q1 .5 1 2v.5q0 2.25-2.25 2.25h-1.5Q9 18.75 9 16.5V16q0-1.5 1-2v-.5q0-2 2-2t2 2z");
}

</style>

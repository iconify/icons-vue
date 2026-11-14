<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyg9cegbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:slider-value" /></template>
<style>
.wyg9cegbl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.75 2.25h-5.5q-2.5 0-2.5 2.5V8.5q0 2.25 2.25 2.25h.625q.5 0 .8.4l.225.3q.506.675 1.35.675t1.35-.675l.225-.3q.3-.4.8-.4H15q2.25 0 2.25-2.25V4.75q0-2.5-2.5-2.5M3 18.75h5.799q.351 2.5 3.201 2.5t3.201-2.5H21q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 17.25h-5.799q-.351-2.5-3.201-2.5t-3.201 2.5H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T2.25 18t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014");
}

</style>

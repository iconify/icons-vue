<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq1x7td4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:temperature-celsius" /></template>
<style>
.iq1x7td4i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.263 17.274q.138-1.878 1.487-3.118V5q0-3.25 3.25-3.25q1.346 0 2.298.952T11.25 5v9.156q1.349 1.24 1.487 3.118q.152 2.065-1.257 3.582T8 22.372q-2.071 0-3.48-1.516t-1.257-3.582M13.995 4.495Q12.75 5.74 12.75 7.5t1.245 3.005T17 11.75t3.005-1.245T21.25 7.5t-1.245-3.005T17 3.25t-3.005 1.245M8.75 17.5V11q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T8 10.25t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T7.25 11v6.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>

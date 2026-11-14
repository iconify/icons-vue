<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9j_wcsyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rotate-angle" /></template>
<style>
.c9j_wcsyh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.5 19.75H4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T3.25 19q0-.137.049-.266q.048-.128.139-.231l11.5-13q.099-.112.233-.177t.283-.075t.29.04q.141.048.253.147t.177.233t.075.283t-.04.29q-.048.141-.147.253l-5.722 6.468q2.151 2.215 2.382 5.285H20.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014M16 9.5Q16 7 18.5 7q1.036 0 1.768.732T21 9.5t-.732 1.768T18.5 12Q16 12 16 9.5m-6.658 4.593L5.665 18.25h5.551q-.22-2.398-1.874-4.157");
}

</style>

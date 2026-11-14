<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfy4x5jrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:network-waterfall" /></template>
<style>
.yfy4x5jrf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 21.5v-19q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q3.074 1.75 3 1.75t-.146.014t-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146v19q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146m4-18.25h4.5q2.5 0 2.5 2.5q0 1.036-.732 1.768t-1.768.732h-4.5q-1.036 0-1.768-.732T5.25 5.75q0-2.5 2.5-2.5m10.268 6.982Q17.286 9.5 16.25 9.5h-4.5q-2.5 0-2.5 2.5q0 1.036.732 1.768t1.768.732h4.5q1.036 0 1.768-.732T18.75 12t-.732-1.768M15.25 15.75h4.5q1.036 0 1.768.732t.732 1.768t-.732 1.768t-1.768.732h-4.5q-2.5 0-2.5-2.5t2.5-2.5");
}

</style>

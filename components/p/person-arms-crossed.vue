<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igc67abml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:person-arms-crossed" /></template>
<style>
.igc67abml {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 6.5q0-1.76 1.245-3.005T12 2.25t3.005 1.245T16.25 6.5t-1.245 3.005T12 10.75T8.995 9.505T7.75 6.5m-4 10.5v4.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V17q0-3.5 6.75-3.5t6.75 3.5v4.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V17q0-5-8.25-5t-8.25 5m2.5.5q0-2.5 2.5-2.5h6.5q2.5 0 2.5 2.5t-2.5 2.5h-6.5q-2.5 0-2.5-2.5");
}

</style>

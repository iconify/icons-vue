<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2jt0ng8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:photojournalist" /></template>
<style>
.z2jt0ng8z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 6.5q0-1.76 1.245-3.005T12 2.25t3.005 1.245T16.25 6.5t-1.245 3.005T12 10.75T8.995 9.505T7.75 6.5m7.125 6.25h-5.75q-2.922 0-3.314 2.53q-3.561.33-3.561 4.22v2q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2q0-2.345 2-2.69v2.065q0 3.375 3.375 3.375h5.75q3.375 0 3.375-3.375V16.81q2 .345 2 2.69v2q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2q0-3.89-3.561-4.22q-.392-2.53-3.314-2.53M9.5 17.5Q9.5 15 12 15q1.036 0 1.768.732T14.5 17.5t-.732 1.768T12 20q-2.5 0-2.5-2.5");
}

</style>

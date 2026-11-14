<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="murofwwqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:user-manager" /></template>
<style>
.murofwwqr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 7.5q0-1.968 1.391-3.359T12 2.75t3.359 1.391T16.75 7.5t-1.391 3.359T12 12.25t-3.359-1.391T7.25 7.5m-4 12V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h16q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-1.5q0-5.211-6.438-5.747q-.14-.012-.276.028q-.135.04-.246.127L12 15.3l-1.79-1.392q-.111-.087-.246-.127q-.136-.04-.276-.028q-6.438.536-6.438 5.747m10.03-3.452q-.396-.548-1.071-.548h-.418q-.676 0-1.071.548t-.182 1.189l.093.277q.042.126.096.236q-.054.11-.097.237l-.339 1.017q-.417 1.255.615 2.081q1.094.876 2.188.001q1.032-.827.615-2.082l-.34-1.018q-.042-.126-.096-.236q.054-.11.097-.237l.092-.276q.213-.641-.182-1.189");
}

</style>

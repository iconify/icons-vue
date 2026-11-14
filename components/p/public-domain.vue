<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2llehgno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:public-domain" /></template>
<style>
.h2llehgno {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m9-1.749V7.5q0-1.25 1.25-1.25t1.25 1.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-2.75-2.75-2.75T9.25 7.5v3.014q-1.75.681-1.75 3.111v.75q0 3.375 3.375 3.375h2.25q3.375 0 3.375-3.375v-.75q0-3.375-3.375-3.375h-2.25z");
}

</style>

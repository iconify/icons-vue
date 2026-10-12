<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2jwb2oxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stage-lights-sharp" /></template>
<style>
.q2jwb2oxs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.5h18.5M7 3.5v3m10-3v3m-10.9 0h2.4l.13.59l.74 3.32l.13.59h-5l.13-.59l.74-3.32l.13-.59zm10 0h2.4l.13.59l.74 3.32l.13.59h-5l.13-.59l.74-3.32l.13-.59zM4.75 14L3.5 21.25M9.25 14l1.25 7.25M14.75 14l-1.25 7.25M19.25 14l1.25 7.25");
}

</style>

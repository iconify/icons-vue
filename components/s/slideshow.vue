<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="falwehnnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:slideshow" /></template>
<style>
.falwehnnl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 2.25H6q-1.76 0-3.005 1.245T1.75 6.5V12q0 1.76 1.245 3.005T6 16.25h5.25v1.809l-4.114 2.285q-.065.036-.121.084t-.102.106t-.08.123t-.054.137t-.026.145t.002.147t.031.143q.023.071.058.135q.073.131.19.223q.117.093.26.134t.292.024q.148-.017.278-.089L12 19.358l4.136 2.298q.064.035.135.058q.07.023.143.031q.074.009.147.002q.074-.006.145-.026t.137-.054q.065-.034.123-.08t.106-.102t.084-.121t.058-.135t.031-.143q.009-.074.002-.147q-.006-.074-.026-.145t-.054-.137q-.034-.065-.08-.123t-.102-.106t-.121-.084l-4.114-2.285V16.25H18q1.76 0 3.005-1.245T22.25 12V6.5q0-1.76-1.245-3.005T18 2.25m-5.36 4.984l.001.001l.155.094q1.078.659 1.078 1.921t-1.077 1.92l-.157.096q-1.113.679-2.251.041q-1.139-.639-1.139-1.944v-.226q0-1.305 1.139-1.944q1.138-.638 2.251.041");
}

</style>

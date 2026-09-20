<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt3sl-vpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wrist" /></template>
<style>
.yt3sl-vpp {
  fill: currentColor;
  d: path("M11.192 20.708L6.485 16H1.692V8h4.293l1.292-1.298q.344-.341.79-.521Q8.512 6 8.998 6h9.81q.212 0 .356.144t.144.357t-.144.356t-.356.143h-4.5v2.173h6.5q.212 0 .356.144t.144.357t-.144.356t-.356.143h-6.5v2.154h7.5q.212 0 .356.144t.144.357t-.144.356t-.356.143h-7.5V15.5h5.5q.212 0 .356.144t.144.357t-.144.356t-.356.143H11.51l.534 1.07q.348.701.205 1.456t-.683 1.295z");
}

</style>

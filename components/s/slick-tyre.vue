<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kylrfubvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:slick-tyre" /></template>
<style>
.kylrfubvp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.959 5.459Q1.25 8.169 1.25 12t2.709 6.541q2.71 2.709 6.541 2.709h3q3.831-.001 6.539-2.71T22.747 12t-2.708-6.54T13.5 2.75h-3q-3.831 0-6.541 2.709m15.019 12.02q-1.241 1.242-2.764 1.805q.426-.342.827-.743Q19.75 15.831 19.75 12t-2.709-6.541q-.401-.401-.827-.743q1.523.563 2.764 1.805q2.269 2.27 2.269 5.479t-2.269 5.479M7.141 8.641Q8.532 7.25 10.5 7.25t3.359 1.391T15.25 12t-1.391 3.359T10.5 16.75t-3.359-1.391T5.75 12t1.391-3.359");
}

</style>

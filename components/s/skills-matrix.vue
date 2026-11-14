<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4hzh3b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:skills-matrix" /></template>
<style>
.y4hzh3b6s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 3.5q2 0 2 2t-2 2t-2-2t2-2m8.5 2q0-2-2-2t-2 2t2 2t2-2m4.5-2q2 0 2 2t-2 2t-2-2t2-2M16 12q0-2.5 2.5-2.5q1.036 0 1.768.732T21 12t-.732 1.768t-1.768.732Q16 14.5 16 12m-8.5 0q0-2-2-2t-2 2t2 2t2-2m4.5-2q2 0 2 2t-2 2t-2-2t2-2m0 6q-2.5 0-2.5 2.5T12 21q1.036 0 1.768-.732T14.5 18.5t-.732-1.768T12 16m4 2.5q0-2.5 2.5-2.5q1.036 0 1.768.732T21 18.5t-.732 1.768T18.5 21Q16 21 16 18.5m-8.5 0q0-2-2-2t-2 2t2 2t2-2");
}

</style>

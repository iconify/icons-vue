<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xarlxibrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:p2p-sharp" /></template>
<style>
.xarlxibrc {
  fill: currentColor;
  d: path("M2 19.116V3h8.808v5.73h-2.5q-1.362 0-2.316.955t-.953 2.317t.959 2.325t2.329.962h2.48v3.827zM6.874 6.564q.184-.186.184-.47q0-.285-.186-.468t-.47-.184t-.468.186t-.184.47q0 .285.186.468t.47.184q.285 0 .468-.186m.76 5.957q-.211-.21-.211-.52t.21-.521q.21-.21.52-.21t.521.21q.21.209.21.52t-.21.52t-.52.21t-.52-.21m3.846 0q-.21-.209-.21-.52t.21-.52q.209-.21.52-.21t.52.21q.21.209.21.52t-.21.52q-.209.21-.52.21t-.52-.21M13.192 21v-5.712h2.481q1.362 0 2.316-.954t.953-2.317t-.953-2.325t-2.316-.961h-2.48V4.885H22V21zm2.115-8.48q-.21-.209-.21-.52t.209-.52t.52-.21t.521.21q.21.209.21.52t-.21.52q-.209.21-.52.21q-.31 0-.52-.21m2.76-4.071q.183-.186.183-.47t-.186-.468t-.47-.184q-.285 0-.468.186t-.184.47t.186.468t.47.184q.285 0 .468-.186");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyr6pgbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:outlier" /></template>
<style>
.hyr6pgbra {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 6.25q0-1.76 1.245-3.005T17.75 2t3.005 1.245T22 6.25t-1.245 3.005T17.75 10.5t-3.005-1.245T13.5 6.25M6.25 13q0-2 2-2t2 2q0 1.5-1.125 1.875Q8.75 15 8.25 15q-1.3 0-1.755-.845q-.043.622-.435 1.1q.092-.005.19-.005q1.364 0 1.798.93q.184-1.007 1.077-1.305q.375-.125.875-.125q2 0 2 2t-2 2q-1.364 0-1.798-.93q-.073.403-.261.693q.148-.013.309-.013q2 0 2 2t-2 2t-2-2q0-.786.309-1.263q-.148.013-.309.013q-.29 0-.538-.042Q6 19.669 6 20.25q0 .828-.586 1.414T4 22.25q-2 0-2-2t2-2q.23 0 .441.045q-.191-.427-.191-1.045q0-.775.3-1.25l-.05.001q-.829 0-1.415-.587Q2.5 14.829 2.5 14t.585-1.414q.586-.587 1.415-.587t1.415.587q.202.203.335.435z");
}

</style>

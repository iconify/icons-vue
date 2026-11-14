<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enm1j0zmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:trip-computer" /></template>
<style>
.enm1j0zmt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 4.25H6q-1.76 0-3.005 1.245T1.75 8.5v7q0 1.76 1.245 3.005T6 19.75h12q1.76 0 3.005-1.245T22.25 15.5v-7q0-1.76-1.245-3.005T18 4.25m-2.674 4.5q.337-1.5 2.174-1.5q2.25 0 2.25 2.25t-2.25 2.25q-1.837 0-2.174-1.5H14.5q-1.75 0-1.75 1.75q0 3.25-3.25 3.25h-.826q-.337 1.5-2.174 1.5q-2.25 0-2.25-2.25t2.25-2.25q1.837 0 2.174 1.5H9.5q1.75 0 1.75-1.75q0-3.25 3.25-3.25z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qz-iq3bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pickleball-ball" /></template>
<style>
.qz-iq3bgm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12M12 5Q9.5 5 9.5 7.5T12 10q1.036 0 1.768-.732T14.5 7.5t-.732-1.768T12 5m-7 7q0-2.5 2.5-2.5q1.036 0 1.768.732T10 12t-.732 1.768T7.5 14.5Q5 14.5 5 12m9 0q0-2.5 2.5-2.5T19 12t-2.5 2.5T14 12m-2 2q-2.5 0-2.5 2.5T12 19q1.036 0 1.768-.732T14.5 16.5t-.732-1.768T12 14");
}

</style>

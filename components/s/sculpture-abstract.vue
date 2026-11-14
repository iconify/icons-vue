<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndwv76bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sculpture-abstract" /></template>
<style>
.ndwv76bpr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.067 8.733q-.51 4.787 2.721 8.201q-.441.183-.806.548q-.732.732-.732 1.768v.5q0 1.036.732 1.768t1.768.732h6.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768t-1.768-.732H9.772Q6.06 13.579 6.558 8.892Q7.052 4.25 11.5 4.25q3.875 0 4.649 3q.763 2.956-2.484 4.579q-.834.417-1.36.305q-.312-.067-.417-.341q-.395-1.027 1.081-2.207q.057-.046.105-.103t.083-.121t.058-.135t.03-.144q.009-.074.002-.147q-.006-.074-.027-.145t-.054-.136t-.08-.124q-.046-.057-.103-.105t-.121-.083t-.135-.058t-.144-.03q-.074-.009-.147-.002q-.074.006-.145.027t-.136.054t-.124.08q-2.332 1.867-1.544 3.918q.398 1.033 1.505 1.269q1.04.221 2.343-.43q4.332-2.166 3.266-6.296Q16.537 2.75 11.5 2.75q-5.797 0-6.433 5.983");
}

</style>

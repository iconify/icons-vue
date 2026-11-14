<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5339f_be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:massage-hands" /></template>
<style>
.t5339f_be {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 5.75Q7.5 2.5 12 2.5q1.78 0 3.068.858Q16.5 4.313 16.5 5.75q0 1.208-1.012 2.075Q18.75 8.567 18.75 11q0 1.822-1.829 2.695q.538.175 1.036.393q2.793 1.222 2.793 3.162t-2.793 3.162Q15.471 21.5 12 21.5t-5.957-1.088Q3.25 19.19 3.25 17.25t2.793-3.162q.498-.218 1.036-.392Q5.25 12.822 5.25 11q0-2.341 3.021-3.116Q7.5 7.095 7.5 5.75");
}

</style>

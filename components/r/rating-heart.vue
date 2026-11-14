<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arg4p5bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rating-heart" /></template>
<style>
.arg4p5bid {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.614 11.643Q7.5 9.175 7.5 6.5q0-2.75 2.75-2.75q1.014 0 1.75.622q.736-.622 1.75-.622q2.75 0 2.75 2.75q0 2.675-4.114 5.143q-.088.053-.186.08t-.2.027t-.2-.027t-.186-.08M2 15.75q0 2.675 4.114 5.143q.088.053.186.08t.2.027t.2-.027t.186-.08Q11 18.425 11 15.75Q11 13 8.25 13q-1.014 0-1.75.622Q5.764 13 4.75 13Q2 13 2 15.75m15.114 5.143Q13 18.425 13 15.75Q13 13 15.75 13q1.014 0 1.75.622q.736-.622 1.75-.622Q22 13 22 15.75q0 2.675-4.114 5.143q-.088.053-.186.08t-.2.027t-.2-.027t-.186-.08");
}

</style>

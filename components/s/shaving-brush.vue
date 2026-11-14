<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwy51kb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shaving-brush" /></template>
<style>
.qwy51kb-x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.829 12.335Q5.433 9.544 6.811 6.33Q8.345 2.75 12 2.75t5.189 3.58q1.378 3.214-.018 6.005q-.047.094-.117.171t-.16.132q-.089.055-.189.083q-.101.029-.205.029h-1.286q.036.232.036.5q0 .586-.172 1q1.672.914 1.672 3.5q0 1.657-1.172 2.828q-1.171 1.172-2.828 1.172h-1.5q-1.657 0-2.828-1.172Q7.25 19.407 7.25 17.75q0-2.586 1.672-3.5q-.172-.414-.172-1q0-.268.036-.5H7.5q-.104 0-.205-.029q-.1-.028-.189-.083t-.16-.132t-.117-.171");
}

</style>

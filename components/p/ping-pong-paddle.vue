<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydtvt1bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ping-pong-paddle" /></template>
<style>
.ydtvt1bch {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 9.5q0-3.003 2.123-5.127T14.5 2.25t5.127 2.123T21.75 9.5t-2.123 5.127q-.673.672-1.435 1.132q.15-.009.308-.009q2.75 0 2.75 2.75t-2.75 2.75t-2.75-2.75q0-1.288.603-1.973q-.88.223-1.853.223q-1.949 0-3.528-.895q-.156.512-.563.918l-2.475 2.475q-.659.66-1.591.66t-1.591-.66q-.66-.659-.66-1.591t.66-1.591l2.475-2.475q.407-.407.918-.563Q7.25 11.449 7.25 9.5");
}

</style>

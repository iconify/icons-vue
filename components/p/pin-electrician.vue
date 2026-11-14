<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrsfqpbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-electrician" /></template>
<style>
.rrsfqpbip {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m5.906 2.594q.72-.95 1.832-.521t1.007 1.615l-.108 1.245q-.028.329.194.572q.223.243.553.243h.364q1.073 0 1.53.971t-.227 1.798l-2.864 3.461q-.747.905-1.814.414q-1.066-.492-.864-1.647l.194-1.118q.06-.344-.165-.612q-.224-.267-.573-.267H9.5q-1.08 0-1.561-.968q-.48-.967.172-1.828z");
}

</style>

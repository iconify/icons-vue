<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzc9fbbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:meeting-chat" /></template>
<style>
.nzc9fbbqn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 2.75H6q-1.76 0-3.005 1.245T1.75 7v4q0 1.76 1.245 3.005T6 15.25h4.5V14q0-4 4-4h2.75V7q0-1.76-1.245-3.005T13 2.75M11.75 14q0-2.75 2.75-2.75h5q2.75 0 2.75 2.75v3q0 2.75-2.75 2.75h-3.26l-3.304 2.36q-.06.043-.128.074q-.067.03-.139.047q-.072.016-.146.019q-.073.002-.146-.01t-.142-.038q-.069-.027-.132-.066t-.117-.089q-.053-.051-.096-.111q-.14-.196-.14-.436zm1.5 0v6.043l2.314-1.653q.196-.14.436-.14h3.5q1.25 0 1.25-1.25v-3q0-1.25-1.25-1.25h-5q-1.25 0-1.25 1.25m2.755.005L16.01 14H14.5v.991q.829-.309 1.505-.986");
}

</style>

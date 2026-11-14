<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dh5ji7big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pure-substance" /></template>
<style>
.dh5ji7big {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.212 3.788q.464.463.787.984q.324-.522.788-.986q1.538-1.538 3.713-1.538t3.713 1.538T21.75 7.5q.001 2.175-1.537 3.714q-.462.462-.983.786q.521.324.983.786q1.538 1.539 1.537 3.714q.001 2.175-1.537 3.714q-1.538 1.538-3.713 1.538t-3.713-1.538q-.464-.464-.788-.986q-.323.521-.787.984Q9.675 21.75 7.5 21.75t-3.712-1.538Q2.25 18.675 2.25 16.5t1.538-3.712q.463-.464.985-.788q-.522-.324-.985-.788Q2.25 9.675 2.25 7.5t1.538-3.712Q5.325 2.25 7.5 2.25t3.712 1.538m1.575 8.998q.462-.462.983-.786q-.521-.324-.983-.786q-.464-.464-.788-.986q-.323.521-.787.984q-.463.464-.985.788q.522.324.985.788q.464.463.787.984q.324-.522.788-.986");
}

</style>

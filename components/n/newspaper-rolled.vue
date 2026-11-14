<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pngsrnbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:newspaper-rolled" /></template>
<style>
.pngsrnbes {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 12q0-6.75 3.25-6.75h11.5q3.25 0 3.25 6.75t-3.25 6.75H6q-3.25 0-3.25-6.75m10.5 5.25h4.25q1.75 0 1.75-5.25T17.5 6.75h-4.25zm-1.5-10.5H8.342Q9.25 8.432 9.25 12t-.908 5.25h3.408z");
}

</style>

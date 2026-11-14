<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn81dxk3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:nanotechnology" /></template>
<style>
.nn81dxk3p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.625 2.5h-4.75q-1.398 0-2.386.989q-.989.988-.989 2.386v4.75q0 1.398.989 2.386q.988.989 2.386.989H7.5v3.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5.792q.354 3 3.708 3q3.75 0 3.75-3.75T17.75 14q-3.354 0-3.708 3H9v-3h1.625q1.398 0 2.386-.989q.989-.988.989-2.386v-4.75q0-1.398-.989-2.386q-.988-.989-2.386-.989m-2.875 3h1Q11 5.5 11 7.75v1Q11 11 8.75 11h-1Q5.5 11 5.5 8.75v-1q0-2.25 2.25-2.25");
}

</style>

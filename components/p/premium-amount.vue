<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxk6vrtph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:premium-amount" /></template>
<style>
.fxk6vrtph {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.413 2.25H5.625q-1.398 0-2.386.989q-.989.988-.989 2.386v3.788q0 1.398.989 2.386l6.375 6.375q1.281 1.281 2.561 1.187Q12 18.717 12 18q0-2.071 1.464-3.536Q14.929 13 17 13h2q.079 0 .157.002q.711-1.694-.983-3.388l-6.375-6.375q-.988-.989-2.386-.989M5.25 7.5q0-2.25 2.25-2.25T9.75 7.5T7.5 9.75T5.25 7.5M17 14.25q-3.75 0-3.75 3.75T17 21.75h2q3.75 0 3.75-3.75T19 14.25zM14.75 18q0-2.25 2.25-2.25T19.25 18T17 20.25T14.75 18m6.5 0q0 1.371-.835 1.906q.335-.785.335-1.906t-.335-1.906q.835.535.835 1.906");
}

</style>

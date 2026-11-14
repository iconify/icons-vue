<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gilrj0bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wrestling-mat-circle" /></template>
<style>
.gilrj0bio {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.259 5.25H6.866q-1.952.001-2.425 1.894l-2.125 8.5q-.295 1.183.455 2.144t1.97.962h12.393q1.952-.001 2.425-1.894l2.125-8.5q.295-1.183-.455-2.144t-1.97-.962M6.75 12q0-1.644 1.652-2.745Q9.909 8.25 12 8.25t3.598 1.005Q17.25 10.356 17.25 12t-1.652 2.745Q14.091 15.75 12 15.75t-3.598-1.005Q6.75 13.644 6.75 12");
}

</style>

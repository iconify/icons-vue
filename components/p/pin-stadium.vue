<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkhun0bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-stadium" /></template>
<style>
.fkhun0bko {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 3.75h4q3.417 0 5.834 2.416T22.25 12t-2.416 5.834Q17.417 20.25 14 20.25h-4q-3.417 0-5.834-2.416T1.75 12t2.416-5.834Q6.583 3.75 10 3.75m2 3h-2q-2.175 0-3.712 1.538Q4.75 9.825 4.75 12t1.538 3.712Q7.825 17.25 10 17.25h4q2.175 0 3.712-1.538Q19.25 14.175 19.25 12t-1.538-3.712Q16.175 6.75 14 6.75z");
}

</style>

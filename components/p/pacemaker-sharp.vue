<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbo75ya3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pacemaker-sharp" /></template>
<style>
.fbo75ya3k {
  fill: currentColor;
  d: path("M4.025 20.975Q3 19.95 3 18.5v-7.925q-.675-.65-1.338-1.312T1 7.65q0-.675.488-1.162T2.65 6q.4 0 .738.175t.612.45q.275-.275.613-.45T5.35 6q.675 0 1.163.488T7 7.65q0 .95-.663 1.613T5 10.575V18.5q0 .625.438 1.063T6.5 20t1.063-.437T8 18.5V7q0-2.075 1.463-3.537T13 2t3.538 1.463T18 7v.1q1.725.35 2.863 1.713T22 12v5q0 2.075-1.463 3.538T17 22t-3.537-1.463T12 17v-5q0-1.825 1.138-3.187T16 7.1V7q0-1.25-.875-2.125T13 4t-2.125.875T10 7v11.5q0 1.45-1.025 2.475T6.5 22t-2.475-1.025m11.563-5.387Q15 16.175 15 17t.588 1.413T17 19t1.413-.587T19 17t-.587-1.412T17 15t-1.412.588");
}

</style>

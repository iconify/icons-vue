<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnwv-tbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:weather-mix-sharp" /></template>
<style>
.fnwv-tbsv {
  fill: currentColor;
  d: path("M12.351 21.642q-.293-.28-.293-.694q0-.184.064-.363q.065-.18.213-.321l.723-.668l.723.668q.148.142.212.32q.065.18.065.364q0 .414-.293.694t-.707.281t-.707-.28m-2.743-1.124l-.646-.646l2.546-2.546l.646.646zm6.45-1.5l-1.096-1.096l1.096-1.096l1.096 1.096zm-9 0l-1.096-1.096l1.096-1.096l1.096 1.096zM7.5 15.5q-2.083 0-3.541-1.459Q2.5 12.583 2.5 10.5q0-1.94 1.308-3.356t3.275-1.633q.742-1.405 2.033-2.208Q10.408 2.5 12 2.5q2.154 0 3.701 1.428t1.801 3.559q1.84.111 2.92 1.28Q21.5 9.937 21.5 11.5q0 1.664-1.168 2.832T17.5 15.5z");
}

</style>

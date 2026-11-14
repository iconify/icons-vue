<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d11ho0bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:record" /></template>
<style>
.d11ho0bhy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m3.536 3.536Q9.825 6.75 12 6.75t3.712 1.538Q17.25 9.825 17.25 12t-1.538 3.712Q14.175 17.25 12 17.25t-3.712-1.538Q6.75 14.175 6.75 12t1.538-3.712M15.75 12q0 3.75-3.75 3.75T8.25 12q0-1.875.938-2.812q.937-.938 2.812-.938q3.75 0 3.75 3.75");
}

</style>

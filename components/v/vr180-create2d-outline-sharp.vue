<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsgbwgf1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vr180-create2d-outline-sharp" /></template>
<style>
.hsgbwgf1e {
  fill: currentColor;
  d: path("M8 16.712q-2.252-.656-3.626-2.507T3 10q0-2.931 2.034-4.966Q7.07 3 10 3q2.354 0 4.205 1.374T16.712 8H15.65Q15 6.2 13.463 5.1T10 4Q7.5 4 5.75 5.75T4 10q0 1.925 1.1 3.463T8 15.65zM10.385 21V10.385H21V21zm1-1H20v-8.615h-8.615zm1.192-1.192h6.23l-1.915-2.5l-1.7 2.25l-1.2-1.65zM9.825 9.825");
}

</style>

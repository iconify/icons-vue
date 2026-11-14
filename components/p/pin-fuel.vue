<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb2jlkb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-fuel" /></template>
<style>
.cb2jlkb5r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.125 2.25h4.75q1.398 0 2.386.989q.989.988.989 2.386V9.25H16q2.25 0 2.25 2.25v5q0 .75.75.75t.75-.75V7.311L17.47 5.03q-.106-.105-.163-.243T17.25 4.5t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043T18 3.75t.146.014q.073.015.141.043t.13.069q.061.041.113.094l2.5 2.5q.106.105.163.243T21.25 7v9.5q0 2.25-2.25 2.25t-2.25-2.25v-5q0-.75-.75-.75h-1.75v7.625q0 3.375-3.375 3.375h-4.75q-3.375 0-3.375-3.375V5.625q0-1.398.989-2.386q.988-.989 2.386-.989M9 5.25H8q-2.25 0-2.25 2.25V8q0 2.25 2.25 2.25h1q2.25 0 2.25-2.25v-.5q0-2.25-2.25-2.25");
}

</style>

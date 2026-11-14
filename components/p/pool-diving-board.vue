<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt0bv3bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pool-diving-board" /></template>
<style>
.nt0bv3bxb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.25 5.75H3.75q-2 0-2 2q0 1.265.801 1.73q-.261.503-.235 1.113l.375 9q.089 2.157 2.248 2.157h.181q2.07 0 2.242-2.063l.75-8.999q.042-.503-.111-.938h1.878q-.629.561-.629 1.75q0 2.25 2.25 2.25t2.25-2.25q0-1.189-.629-1.75h3.129q2 0 2-2t-2-2m-1.8 13.15q-2.45-1.837-4.9 0q-.059.044-.108.099q-.05.055-.087.119q-.038.063-.063.133q-.024.07-.034.143t-.007.147t.022.145t.051.138t.076.126q.09.119.218.195t.276.097t.292-.015t.264-.127q1.55-1.162 3.1 0q2.45 1.838 4.9 0q1.526-1.144 2.57-.274q.057.047.121.083q.065.035.136.057q.07.022.144.03t.147.001t.144-.028t.137-.055q.065-.034.122-.081q.058-.046.105-.103t.083-.121q.035-.065.057-.136q.022-.07.03-.144t.001-.147t-.028-.144t-.055-.137q-.034-.065-.081-.122q-.046-.058-.103-.105q-1.956-1.63-4.43.226q-1.55 1.163-3.1 0");
}

</style>

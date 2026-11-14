<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yficp7b5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:user-edit" /></template>
<style>
.yficp7b5a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.818 5.068Q4.5 6.386 4.5 8.25t1.318 3.182T9 12.75t3.182-1.318T13.5 8.25t-1.318-3.182T9 3.75T5.818 5.068m8.7 8.645l.155-.698q.142-.641.606-1.104l3.316-3.315q.582-.583 1.405-.583t1.406.583t.582 1.405q0 .823-.583 1.406l-3.316 3.315q-.462.464-1.102.606l-.7.155q-.794.177-1.37-.399t-.399-1.37M1.75 20q0-2.427 2.213-4.015Q6.03 14.5 9 14.5t5.037 1.485Q16.25 17.573 16.25 20q0 1.75-1.75 1.75h-11q-1.75 0-1.75-1.75");
}

</style>

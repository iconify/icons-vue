<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah8wzhb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:purchase-offer" /></template>
<style>
.ah8wzhb7m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.25 1.75h3.5q2.278 0 3.889 1.611T19.25 7.25t-1.611 3.889t-3.889 1.611h-1v8.75q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-8.75h-1q-2.278 0-3.889-1.611T4.75 7.25t1.611-3.889T10.25 1.75M9.236 6.749q-.736.67-.736 1.665v.211q0 1.625 1.625 1.625h3.75q1.625 0 1.625-1.625v-.211q0-.995-.736-1.665l-1.251-1.137q-1.513-1.376-3.027 0z");
}

</style>

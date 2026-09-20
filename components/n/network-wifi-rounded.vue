<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuprshb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:network-wifi-rounded" /></template>
<style>
.zuprshb5a {
  fill: currentColor;
  d: path("M4.35 10.5q1.675-1.2 3.625-1.85T12 8t4.025.65t3.625 1.85l1.45-1.45q-1.975-1.5-4.3-2.275T12 6t-4.8.775T2.9 9.05zm6.225 9.075l-9.05-9.05q-.3-.3-.45-.675t-.15-.75q0-.425.175-.812t.525-.688Q3.675 5.825 6.5 4.913T12 4t5.5.913T22.375 7.6q.35.3.525.688t.175.812q0 .375-.15.75t-.45.675l-9.05 9.05q-.3.3-.675.45t-.75.15t-.75-.15t-.675-.45");
}

</style>

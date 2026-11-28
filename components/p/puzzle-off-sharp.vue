<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p09dd0bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:puzzle-off-sharp" /></template>
<style>
.p09dd0bqe {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 7L3 7L3 11L4 11C5.6569 11 7 12.3431 7 14C7 15.6569 5.6569 17 4 17L3 17L3 21L17 21L17 17M20.4067 16.052L20.7819 15.1251C20.9226 14.7776 21 14.3979 21 14C21 12.3431 19.6569 11 18 11L17 11L17 7L13 7L13 6C13 4.3431 11.6569 3 10 3C9.6021 3 9.2224 3.0774 8.8749 3.2181L7.948 3.5933M1.7071 1.7071L22.2929 22.2929");
}

</style>

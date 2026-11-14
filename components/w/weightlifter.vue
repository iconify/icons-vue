<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emcfmdb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:weightlifter" /></template>
<style>
.emcfmdb3i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.251 11.322za1.5 1.5 0 0 1 2.114.185l5.142 6.128a1.5 1.5 0 0 1-.185 2.114a1.5 1.5 0 0 1-2.113-.185l-5.142-6.129a1.5 1.5 0 0 1 .184-2.113m8.427-7.071za1.5 1.5 0 0 1 2.113.185l5.142 6.129a1.5 1.5 0 0 1-.184 2.113a1.5 1.5 0 0 1-2.114-.185l-5.142-6.128a1.5 1.5 0 0 1 .185-2.114m-3.742 10.32l6.128-5.142m-11.107 9.32L6.638 16.5m10.724-9l2.681-2.249");
}

</style>

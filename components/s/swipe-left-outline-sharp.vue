<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb0kvb38k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:swipe-left-outline-sharp" /></template>
<style>
.eb0kvb38k {
  fill: currentColor;
  d: path("M2 7V2h1.5v2.025q1.8-1.475 3.975-2.25T12 1q3.65 0 6.45 1.675T22 7h-1.575q-.95-2.1-3.213-3.3T12 2.5q-2.2 0-4.225.775T4.1 5.5H7V7zm8.575 15L4.6 16l1.575-1.625l2.825.8V6h2v11.825l-2.425-.675l2.85 2.85H18v-7h2v9zM12 15v-5h2v5zm3 0v-4h2v4zm-.475 2");
}

</style>

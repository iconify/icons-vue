<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq9nmbb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stone-wall" /></template>
<style>
.zq9nmbb6v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.609 2.946l4.171-.139a1.75 1.75 0 0 1 1.806 1.662l.075 1.5a1.75 1.75 0 0 1-1.693 1.837l-4.321.135a1.75 1.75 0 0 1-1.802-1.837l.075-1.496a1.75 1.75 0 0 1 1.689-1.662m10.666-.078l4.175.279a1.75 1.75 0 0 1 1.632 1.654l.068 1.298a1.75 1.75 0 0 1-1.802 1.842l-4.316-.135a1.75 1.75 0 0 1-1.693-1.837l.072-1.442a1.75 1.75 0 0 1 1.864-1.659M6.11 10.723l11.725-.195a1.75 1.75 0 0 1 1.776 1.633l.017.253a1.75 1.75 0 0 1-1.718 1.866l-11.781.19a1.73 1.73 0 0 1-1.754-1.845l.018-.268a1.75 1.75 0 0 1 1.717-1.634m-1.521 6.474l4.212-.14a1.75 1.75 0 0 1 1.805 1.639l.031.502a1.75 1.75 0 0 1-1.692 1.858l-4.274.134a1.75 1.75 0 0 1-1.801-1.858l.031-.495a1.75 1.75 0 0 1 1.688-1.64m10.614-.142l4.237.137a1.75 1.75 0 0 1 1.69 1.865l-.025.361a1.75 1.75 0 0 1-1.689 1.633l-4.25.137a1.75 1.75 0 0 1-1.803-1.852l.037-.635a1.75 1.75 0 0 1 1.803-1.646");
}

</style>

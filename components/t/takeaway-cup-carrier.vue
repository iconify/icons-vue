<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wufgtwb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:takeaway-cup-carrier" /></template>
<style>
.wufgtwb-t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.998 14h14.004a1.75 1.75 0 0 1 1.644 2.348l-.727 2a1.75 1.75 0 0 1-1.645 1.152H5.726a1.75 1.75 0 0 1-1.645-1.152l-.727-2A1.75 1.75 0 0 1 4.998 14m1.659-5h2.186a1.5 1.5 0 0 1 1.492 1.649l-.2 2A1.5 1.5 0 0 1 8.643 14H6.857a1.5 1.5 0 0 1-1.492-1.351l-.2-2A1.5 1.5 0 0 1 6.657 9m8.5 0h2.186a1.5 1.5 0 0 1 1.492 1.649l-.2 2A1.5 1.5 0 0 1 17.143 14h-1.786a1.5 1.5 0 0 1-1.492-1.351l-.2-2A1.5 1.5 0 0 1 15.157 9M5.5 6.5H10a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 10 9H5.5a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 5.5 6.5m8.5 0h4.5a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 18.5 9H14a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 14 6.5m-6.25 0v-2m8.5 2v-2");
}

</style>

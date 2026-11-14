<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa65u-vzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:succulent" /></template>
<style>
.fa65u-vzf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.279 8.706q1.2 4.201 4.071 5.897q-.351.217-.638.57q-.75.923-.507 2.087l.521 2.5q.414 1.99 2.447 1.99h5.654q2.033 0 2.447-1.99l.521-2.5q.243-1.164-.507-2.087q-.287-.353-.638-.57q2.871-1.696 4.071-5.897q.02-.071.026-.145q.007-.073-.002-.147q-.008-.073-.031-.143q-.023-.071-.058-.135t-.084-.121q-.048-.056-.106-.102t-.123-.08t-.137-.054q-.15-.043-.305-.022q-3.437.458-5.685 2.493q.034-.517.034-1.062q0-3.762-1.599-6.56q-.101-.178-.279-.279q-.129-.074-.277-.093t-.292.02t-.262.131t-.192.221Q9.75 5.426 9.75 9.188q0 .545.034 1.062q-2.248-2.035-5.685-2.493q-.155-.021-.305.022q-.143.041-.26.134q-.117.092-.19.223q-.072.13-.089.278t.024.292");
}

</style>

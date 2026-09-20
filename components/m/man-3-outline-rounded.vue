<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc5sxib6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:man-3-outline-rounded" /></template>
<style>
.sc5sxib6p {
  fill: currentColor;
  d: path("M10.23 20.942v-5.769h-.96q-.344 0-.576-.232q-.233-.232-.233-.576V9.29q0-.667.475-1.141t1.141-.475h3.846q.667 0 1.141.475t.475 1.14v5.078q0 .343-.233.575q-.232.232-.575.232h-.962v5.77q0 .343-.232.575t-.575.232h-1.923q-.344 0-.576-.232t-.232-.576m1.204-15.2l-.812-.811q-.242-.243-.242-.566t.242-.565l.812-.812q.242-.242.565-.242t.566.242l.811.812q.242.242.242.566t-.242.565l-.811.811q-.243.243-.566.243t-.565-.243");
}

</style>

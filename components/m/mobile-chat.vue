<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svxb4lb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-chat" /></template>
<style>
.svxb4lb6t {
  fill: currentColor;
  d: path("M7.616 22q-.667 0-1.141-.475T6 20.386V3.615q0-.666.475-1.14T7.615 2h8.77q.666 0 1.14.475T18 3.614v4.308h-4.077q-1.365 0-2.279.914t-.913 2.279V21h2.536l2.308-2.308H18v1.693q0 .666-.475 1.14t-1.14.475zm5.5-4.211v-6.667q0-.355.232-.584q.232-.23.575-.23h6.039q.343 0 .575.232t.232.576V15.5q0 .343-.232.576t-.575.232h-5.366zm-.528-11.703q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22");
}

</style>

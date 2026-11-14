<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5-sisb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pharmacy-basket" /></template>
<style>
.l5-sisb9j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.25 2.75h.5Q20 2.75 20 5v.5q0 .553-.232 1.009q.982.505.982 1.991v3.308q.223.19.413.444q.75 1.003.396 2.204l-1.47 5q-.528 1.793-2.398 1.794H6.309q-1.87-.001-2.397-1.794l-1.472-5q-.353-1.201.397-2.204q.08-.106.165-.201Q3 12.026 3 12q0-2.071 1.464-3.536Q5.929 7 8 7t3.536 1.464q1.191 1.192 1.413 2.786h1.301V8.5q0-1.486.982-1.991Q15 6.053 15 5.5V5q0-2.25 2.25-2.25m0 5h-.75q-.75 0-.75.75v2.75h3.411l.089.001V8.5q0-.75-.75-.75zm-6.775 1.775Q9.45 8.5 8 8.5q-3.111 0-3.457 2.765q.144-.015.296-.015h6.587q-.202-.976-.951-1.725");
}

</style>

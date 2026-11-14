<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp7x07bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sports-massage" /></template>
<style>
.lp7x07bbk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 3.75h-5.5q-3.354 0-3.708 3H7.19q-.345-2-2.69-2q-2.75 0-2.75 2.75t2.75 2.75q2.345 0 2.69-2h1.602q.332 2.814 3.304 2.988l-1.833 9.622q-.028.146.003.292q.03.146.114.27q.084.123.208.205q.125.082.272.11q.069.013.14.013h4.5q.065 0 .129-.011t.125-.033t.118-.055q.056-.032.106-.073q.05-.042.092-.091q.043-.049.076-.105t.056-.117t.035-.125l1.884-9.891q3.629-.06 3.629-3.749q0-3.75-3.75-3.75m-6.094 16.5l1.715-9h2.973l-1.715 9z");
}

</style>

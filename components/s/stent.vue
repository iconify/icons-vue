<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4u9mccxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stent" /></template>
<style>
.k4u9mccxv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 18.25q-2.75 0-2.75-6.25T5 5.75h14q2.75 0 2.75 6.25T19 18.25zm9.786-11h-3.072l1.536 3.073zM14.089 12l2.375-4.75h.502Q16.25 8.812 16.25 12t.716 4.75h-.502zm-1.678 0L10.5 8.177L8.589 12l1.911 3.823zm-.697 4.75h3.072l-1.536-3.073zm-2.428-9.5H6.214l1.536 3.073zM6.911 12l-2.304 4.609Q3.75 15.933 3.75 12t.857-4.609zm2.375 4.75L7.75 13.677L6.214 16.75z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xd3s20thz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-quote-opening-32-filled" /></template>
<style>
.xd3s20thz {
  fill: currentColor;
  d: path("M22.5 27a4.5 4.5 0 0 1-4.5-4.5c0-5.453 1.562-9.265 3.161-11.731a15.2 15.2 0 0 1 2.21-2.702c.305-.292.563-.51.75-.659q.142-.11.225-.17q.06-.044.087-.062l.007-.005l.003-.001l.002-.002a1 1 0 0 1 1.11 1.663h.003l-.004.002l-.034.024a9 9 0 0 0-.765.653a13.2 13.2 0 0 0-1.916 2.346c-1 1.543-2.017 3.739-2.518 6.708A4.5 4.5 0 1 1 22.5 27m-13 0A4.5 4.5 0 0 1 5 22.5c0-5.453 1.562-9.265 3.161-11.731a15.2 15.2 0 0 1 2.21-2.702c.305-.292.563-.51.75-.659q.141-.11.225-.17q.06-.044.087-.062l.007-.005l.003-.001l.002-.002a1 1 0 0 1 1.11 1.663h.003l-.004.002l-.034.024a9 9 0 0 0-.765.653a13.2 13.2 0 0 0-1.916 2.346c-1 1.543-2.017 3.739-2.518 6.708A4.5 4.5 0 1 1 9.5 27");
}

</style>

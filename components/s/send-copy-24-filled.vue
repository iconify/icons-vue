<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj6m0lf7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:send-copy-24-filled" /></template>
<style>
.fj6m0lf7y {
  fill: currentColor;
  d: path("M3.997 11.5a1 1 0 0 0-.993.883l-.007.117V17a5.5 5.5 0 0 0 5.279 5.496l.22.004h7.256a2.5 2.5 0 0 0 2.452-2.012h-2.347l-.052.009l-.053.003H8.497a3.5 3.5 0 0 1-3.494-3.296l-.006-.192V12.5a1 1 0 0 0-1-1m3.006-2.013a1 1 0 0 0-.993.883l-.007.117v6.5a2.5 2.5 0 0 0 2.336 2.495l.164.006h10a2.5 2.5 0 0 0 2.495-2.336l.005-.164v-6.49a1 1 0 0 0-1.993-.116l-.007.116v6.49a.5.5 0 0 1-.41.492l-.09.008h-10a.5.5 0 0 1-.492-.41l-.008-.09v-6.501a1 1 0 0 0-1-1m10.706-3.694l-3.498-3.5a1 1 0 0 0-1.32-.083l-.094.083l-3.502 3.5a1 1 0 0 0 1.32 1.498l.094-.084l1.793-1.792v8.84a1 1 0 0 0 .883.993l.117.007a1 1 0 0 0 .993-.883l.007-.117V5.412l1.792 1.795a1 1 0 0 0 1.32.084l.095-.084a1 1 0 0 0 .083-1.32zl-3.498-3.5z");
}

</style>

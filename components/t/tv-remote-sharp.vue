<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yywc-2y3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tv-remote-sharp" /></template>
<style>
.yywc-2y3t {
  fill: currentColor;
  d: path("M14.125 14.125Q15 13.25 15 12t-.875-2.125T12 9t-2.125.875T9 12t.875 2.125T12 15t2.125-.875M7 23V1h10v22zm3.938-9.937Q10.5 12.625 10.5 12t.438-1.062T12 10.5t1.063.438T13.5 12t-.437 1.063T12 13.5t-1.062-.437m1.774-7.35Q13 5.424 13 5t-.288-.712T12 4t-.712.288T11 5t.288.713T12 6t.713-.288");
}

</style>

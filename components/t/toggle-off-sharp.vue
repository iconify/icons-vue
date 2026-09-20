<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9tfpd8og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:toggle-off-sharp" /></template>
<style>
.h9tfpd8og {
  fill: currentColor;
  d: path("M7 18q-2.5 0-4.25-1.75T1 12t1.75-4.25T7 6h10q2.5 0 4.25 1.75T23 12t-1.75 4.25T17 18zm2.125-3.875Q10 13.25 10 12t-.875-2.125T7 9t-2.125.875T4 12t.875 2.125T7 15t2.125-.875");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxgrf0bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:onigiri" /></template>
<style>
.bxgrf0bib {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.705 8.555Q14.486 6.388 12 6.388T8.295 8.555L5.28 13.916q-1.195 2.125.036 4.229q1.23 2.105 3.668 2.105H10q-2.25 0-2.25-2.25v-3q0-2.25 2.25-2.25h4q.932 0 1.591.659T16.25 15v3q0 .932-.659 1.591T14 20.25h1.016q2.438 0 3.668-2.105q1.231-2.104.036-4.229z");
}

</style>

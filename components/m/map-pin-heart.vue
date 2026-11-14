<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgwri608w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-pin-heart" /></template>
<style>
.jgwri608w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 9.5q0 5.842 7.759 12.567q.051.044.108.078q.058.034.121.058q.063.023.129.035t.133.012t.133-.012t.129-.035q.063-.024.121-.058t.108-.078Q20.25 15.342 20.25 9.5q0-3.417-2.416-5.834T12 1.25T6.166 3.666Q3.75 6.083 3.75 9.5m7.891 3.158Q8.5 10.945 8.5 8.5q0-2.25 2.25-2.25q.741 0 1.25.357q.509-.357 1.25-.357q2.25 0 2.25 2.25q0 2.445-3.141 4.158q-.082.045-.174.069q-.091.023-.185.023t-.185-.023q-.092-.024-.174-.069");
}

</style>

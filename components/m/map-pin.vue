<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3bw70bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-pin" /></template>
<style>
.d3bw70bpy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 9.5q0 5.842 7.759 12.567q.051.044.108.078q.058.034.121.058q.063.023.129.035t.133.012t.133-.012t.129-.035q.063-.024.121-.058t.108-.078Q20.25 15.342 20.25 9.5q0-3.417-2.416-5.834T12 1.25T6.166 3.666Q3.75 6.083 3.75 9.5m4.75 0Q8.5 6 12 6t3.5 3.5T12 13T8.5 9.5");
}

</style>

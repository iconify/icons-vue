<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlr620fta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:moons-orbiting" /></template>
<style>
.dlr620fta {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.75 6.25q0-1.693.717-2.669Q13.302 3.25 12 3.25q-3.624 0-6.187 2.563T3.25 12q0 1.302.331 2.467q.976-.717 2.669-.717q4 0 4 4q0 1.693-.717 2.669q1.165.331 2.467.331q3.624 0 6.187-2.563T20.75 12q0-1.302-.331-2.467q-.976.717-2.669.717q-4 0-4-4m4-2.75q2.75 0 2.75 2.75T17.75 9T15 6.25t2.75-2.75m0 4q-1.25 0-1.25-1.25T17.75 5T19 6.25T17.75 7.5M3.5 17.75Q3.5 15 6.25 15T9 17.75T6.25 20.5T3.5 17.75m1.5 0Q5 19 6.25 19t1.25-1.25t-1.25-1.25T5 17.75");
}

</style>

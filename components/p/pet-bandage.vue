<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o59nohmhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pet-bandage" /></template>
<style>
.o59nohmhj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 3q-2.5 0-2.5 2.5T8.75 8t2.5-2.5T8.75 3m6.5 0q-2.5 0-2.5 2.5t2.5 2.5t2.5-2.5t-2.5-2.5M4.5 8.25q-2.5 0-2.5 2.5t2.5 2.5q1.036 0 1.768-.732T7 10.75t-.732-1.768T4.5 8.25m15 0q-2.5 0-2.5 2.5t2.5 2.5t2.5-2.5t-2.5-2.5m-12.953 6q.462-3.5 5.453-3.5t5.453 3.5h.297q2.5 0 2.5 2.5q0 1.036-.732 1.768t-1.768.732h-.33q-.309 1.358-1.812 2.002q-1.514.648-3.608.262q-2.094.386-3.608-.262q-1.503-.644-1.812-2.002h-.33q-1.036 0-1.768-.732T3.75 16.75q0-2.5 2.5-2.5zm1.54 0q.502-2 3.913-2t3.913 2zm6.93 5.623q.54-.231.783-.623H8.2q.243.392.783.623q1.138.488 2.87.142q.147-.03.294 0q1.732.346 2.87-.142");
}

</style>

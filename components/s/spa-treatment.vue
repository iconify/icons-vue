<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onbh6qb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:spa-treatment" /></template>
<style>
.onbh6qb9x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.853 7.735Q9.375 7.24 9.375 4.938q0-2.196 2.346-3.134q.135-.054.279-.054t.279.054q2.346.938 2.346 3.134q0 2.302-2.478 2.797q-.147.03-.294 0m1.897.515h-3.5q-2 0-2 2t2 2H8q-2.25 0-2.25 2.25T8 16.75H5.75q-1.036 0-1.768.732T3.25 19.25t.732 1.768t1.768.732h12.5q1.036 0 1.768-.732t.732-1.768t-.732-1.768t-1.768-.732H16q2.25 0 2.25-2.25T16 12.25h-2.25q2 0 2-2t-2-2");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w45u82kfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:schema-tree" /></template>
<style>
.w45u82kfx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 2.75h-2.5q-1.036 0-1.768.732T2.75 5.25v.5q0 1.036.732 1.768t1.768.732h.5V18.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h4.778q.236 2 2.472 2h5q2.5 0 2.5-2.5v-.5q0-2.5-2.5-2.5h-5q-2.236 0-2.472 2H7.25v-5.5h4.028q.236 2 2.472 2h5q2.5 0 2.5-2.5v-.5q0-2.5-2.5-2.5h-5q-2.236 0-2.472 2H7.25v-2.5h.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768T7.75 2.75");
}

</style>

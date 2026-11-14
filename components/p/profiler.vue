<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl9s1utnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:profiler" /></template>
<style>
.fl9s1utnn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 2.5h2.5Q12 2.5 12 5v.5q0 1.036-.732 1.768T9.5 8H7q-1.036 0-1.768-.732T4.5 5.5V5q0-2.5 2.5-2.5M4.25 9.25h7.5q2.5 0 2.5 2.5v.5q0 2.5-2.5 2.5h-7.5q-2.5 0-2.5-2.5v-.5q0-1.036.732-1.768T4.25 9.25m15.5 0H18q-2.5 0-2.5 2.5v.5q0 2.5 2.5 2.5h1.75q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768T19.75 9.25m1.768 7.482Q20.786 16 19.75 16H4.25q-2.5 0-2.5 2.5v.5q0 2.5 2.5 2.5h15.5q1.036 0 1.768-.732T22.25 19v-.5q0-1.036-.732-1.768");
}

</style>

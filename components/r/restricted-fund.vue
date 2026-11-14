<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8qhx84wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:restricted-fund" /></template>
<style>
.i8qhx84wa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 6q0-.486.173-.899Q3.909 2.75 10.5 2.75q7.75 0 7.75 3.25v7.005Q18.127 13 18 13q-.694 0-1.25.138v-.157Q14.84 14 10.5 14t-6.25-1.019V15.5q0 1.75 6.25 1.75q1.702 0 2.94-.13q-.332.638-.413 1.526q-1.14.104-2.527.104q-7.75 0-7.75-3.25zm14 2.231Q14.84 9.25 10.5 9.25T4.25 8.231v2.519q0 1.75 6.25 1.75t6.25-1.75zm4.268 9.251q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 2.75q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707z");
}

</style>

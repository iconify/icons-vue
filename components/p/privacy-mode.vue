<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rye8z62pg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:privacy-mode" /></template>
<style>
.rye8z62pg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 8.25q0-1.864 1.318-3.182T9 3.75t3.182 1.318T13.5 8.25t-1.318 3.182T9 12.75t-3.182-1.318T4.5 8.25m16.518 9.232q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768m-6.981-1.497q.119.085.231.172Q13 17.07 13 19.25v.5q0 1.118.569 2H3.5q-1.75 0-1.75-1.75q0-2.427 2.213-4.015Q6.03 14.5 9 14.5t5.037 1.485m4.713.515v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 2.75q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707z");
}

</style>

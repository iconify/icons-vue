<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xs0-x-bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rock-balance" /></template>
<style>
.xs0-x-bsp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 3.75Q8.75 1.5 12 1.5q1.243 0 2.154.546q1.096.658 1.096 1.704q0 .5-.16.889q4.66.478 4.66 2.611q0 2.083-4.445 2.588l.054.053q1.391 1.391 1.391 3.359t-1.391 3.359l-.082.079q1.2.151 2.22.423q2.753.734 2.753 2.139t-2.753 2.139Q15.205 22 12 22q-8.25 0-8.25-2.75q0-2.125 4.925-2.608l-.034-.033Q7.25 15.218 7.25 13.25t1.391-3.359l.054-.053Q4.25 9.333 4.25 7.25q0-2.133 4.66-2.611q-.16-.389-.16-.889");
}

</style>

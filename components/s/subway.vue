<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7_q7omme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:subway" /></template>
<style>
.f7_q7omme {
  fill: currentColor;
  d: path("M3 21V8.85q0-1.76.956-3.101t2.629-2.026q1.215-.467 2.663-.595T12 3t2.752.128t2.664.595q1.673.685 2.628 2.026Q21 7.091 21 8.85V21zm5.754-1l1.5-1.654h3.48l1.5 1.654h.882v-.5l-1.089-1.204q1.12-.15 1.739-.91q.619-.761.619-1.886V9q0-1.43-1.443-1.927Q14.5 6.577 12 6.577q-2.275 0-3.83.496T6.615 9v6.5q0 1.125.62 1.895q.619.77 1.738.901L7.884 19.5v.5zM7.5 13.23V9h9v4.23zm6.999 2.886q-.23-.23-.23-.577t.23-.578t.578-.23t.578.23t.23.578t-.23.577q-.23.23-.578.23t-.578-.23m-6.154 0q-.23-.23-.23-.577t.23-.578t.578-.23t.578.23t.23.578t-.23.577q-.23.23-.578.23t-.578-.23");
}

</style>

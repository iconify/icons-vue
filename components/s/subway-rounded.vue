<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg31babvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:subway-rounded" /></template>
<style>
.tg31babvk {
  fill: currentColor;
  d: path("M3 19.385V8.85q0-1.76.956-3.101t2.629-2.026q1.215-.467 2.663-.595T12 3t2.752.128t2.664.595q1.673.685 2.628 2.026Q21 7.091 21 8.85v10.535q0 .67-.472 1.143q-.472.472-1.143.472H4.615q-.67 0-1.143-.472Q3 20.056 3 19.385m4.5-6.154V9h9v4.23zm6.999 2.885q-.23-.23-.23-.577t.23-.578t.578-.23t.578.23t.23.578t-.23.577q-.23.23-.578.23t-.578-.23m-6.154 0q-.23-.23-.23-.577t.23-.578t.578-.23t.578.23t.23.578t-.23.577q-.23.23-.578.23t-.578-.23m1.909 2.23h3.48l1.352 1.487q.068.086.157.127q.09.04.201.04q.327 0 .457-.292t-.085-.527l-.789-.885q1.12-.15 1.739-.91q.619-.761.619-1.886V9q0-1.43-1.443-1.927Q14.5 6.577 12 6.577q-2.275 0-3.83.496T6.615 9v6.5q0 1.125.62 1.895q.619.77 1.738.901l-.794.89q-.216.235-.086.525q.13.289.457.289q.112 0 .198-.05t.154-.117z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4k63o4ar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-mini-golf" /></template>
<style>
.j4k63o4ar {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 16.086V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q7.926 2.25 8 2.25q.072 0 .142.014q.07.013.137.04q.066.026.126.065t.112.088t.094.108q.041.058.071.123t.047.135t.02.141q.7-.263 1.477.002l4.851 1.654q1.525.519 1.525 2.13t-1.525 2.13l-4.851 1.654q-.777.265-1.476.003v5.471Q9.115 16 9.5 16q7.25 0 7.25 3T9.5 22t-7.25-3q0-2.491 5-2.914");
}

</style>

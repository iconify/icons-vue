<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyu2z3bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:trapezoid" /></template>
<style>
.fyu2z3bfn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.914 4.25h6.172q2.461-.001 3.214 2.343l2.812 8.75q.525 1.633-.486 3.02t-2.727 1.387H6.101q-1.716 0-2.727-1.387t-.486-3.02L5.7 6.593q.753-2.344 3.214-2.343");
}

</style>

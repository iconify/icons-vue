<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2s6t-bek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:turn-signal-left" /></template>
<style>
.q2s6t-bek {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.207 10.233l4.349-4.349q.745-.747 1.72-.343t.974 1.46v.249q0 1 1 1h8.5q1.036 0 1.768.732t.732 1.768v2.5q0 1.036-.732 1.768t-1.768.732h-8.5q-1 0-1 1V17q.001 1.055-.974 1.459t-1.721-.343l-4.348-4.349Q1.441 12 3.206 10.233z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdjj668qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:plastering-float" /></template>
<style>
.qdjj668qh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 5.75h8q2.25 0 2.25 2.25T16 10.25h-.25v2h4q1.036 0 1.768.732t.732 1.768t-.732 1.768t-1.768.732H4.25q-2.5 0-2.5-2.5q0-1.036.732-1.768t1.768-.732h4v-2H8q-2.25 0-2.25-2.25T8 5.75m6.25 6.5v-2h-4.5v2z");
}

</style>

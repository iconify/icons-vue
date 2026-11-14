<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g49g3wb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sequence-step" /></template>
<style>
.g49g3wb9b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 1.75h1.5q1.036 0 1.768.732T8.25 4.25v1.5q0 1.036-.732 1.768T5.75 8.25h-1.5q-1.036 0-1.768-.732T1.75 5.75v-1.5q0-1.036.732-1.768T4.25 1.75m8.5 7h-1.5q-2.5 0-2.5 2.5v1.5q0 1.036.732 1.768t1.768.732h1.5q1.036 0 1.768-.732t.732-1.768v-1.5q0-1.036-.732-1.768T12.75 8.75m5.5 7h1.5q1.036 0 1.768.732t.732 1.768v1.5q0 1.036-.732 1.768t-1.768.732h-1.5q-1.036 0-1.768-.732t-.732-1.768v-1.5q0-2.5 2.5-2.5");
}

</style>

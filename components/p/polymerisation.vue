<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf5phacrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:polymerisation" /></template>
<style>
.yf5phacrh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 8.75h.5q2.613 0 3.125 2.1q.512-2.1 3.125-2.1h.5q2.613 0 3.125 2.1q.512-2.1 3.125-2.1h.5q1.346 0 2.298.952T22.25 12q0 3.25-3.25 3.25h-.5q-2.613 0-3.125-2.1q-.512 2.1-3.125 2.1h-.5q-2.613 0-3.125-2.1q-.512 2.1-3.125 2.1H5q-3.25 0-3.25-3.25q0-1.346.952-2.298T5 8.75");
}

</style>

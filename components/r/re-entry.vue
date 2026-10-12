<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw-qurbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:re-entry" /></template>
<style>
.qw-qurbdu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.64 9.42l7.81 3.22q-1.14 6.67-7.81 7.81l-3.22-7.81q.92-2.3 3.22-3.22M11.6 6.65l-1.06-3.54M8.95 8.95L6.12 6.12m.53 5.48l-3.54-1.06");
}

</style>

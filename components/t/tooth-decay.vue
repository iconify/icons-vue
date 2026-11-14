<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbcbzyb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tooth-decay" /></template>
<style>
.cbcbzyb3o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.737 2.788Q8.122 2.25 7 2.25q-4.25 0-4.25 5.25q0 2.091 1.262 4.767q.588 1.247.755 1.892l.995 5.475q.29 1.741 1.988 1.741q1.672 0 1.98-1.698l1.236-3.953q.2-.599 1.034-.599t1.038.612l1.232 3.94q.308 1.698 1.98 1.698q1.698 0 1.99-1.752l.993-5.464q.166-.645.755-1.892Q21.25 9.591 21.25 7.5q0-5.25-4.25-5.25q-1.122 0-2.737.538q-1.385.462-2.263.462t-2.263-.462M9.25 9.5q0-2.75 2.75-2.75t2.75 2.75T12 12.25T9.25 9.5");
}

</style>

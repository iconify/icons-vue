<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="e6zlq9bfh"/><path class="aav8kfr6u"/><path class="yh4-m8b2w"/><path class="jnu7wevsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:woodturning" /></template>
<style>
.aav8kfr6u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.47 11.02c1.61 0 2.92 5.2 2.92 11.62c0 .25 0 .49-.01.73m-2.82 10.87c-.03.01-.06.01-.09.01m-3.26-23.23c1.6 0 2.91 5.1 2.93 11.44m-2.93 11.79c.86 0 1.64-1.48 2.17-3.83M5.5 11.025h14.162c1.616 0 2.926 5.2 2.926 11.615s-1.31 11.615-2.926 11.615H5.5");
}

.e6zlq9bfh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.66 11.02h16.22c1.62 0 2.93 5.2 2.93 11.62c0 5.25-.88 9.69-2.09 11.12m-6.16.49h-10.9");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.jnu7wevsz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.517 39.707c-3.582 1.397-3.743 2.467-3.743 2.467l-.084.326m1.612-5.092l.301 1.087M27.677 20.96l-.168-1.43m-1.845 2.321l-.722-.799m.722 3.192l-1.177.295");
}

.yh4-m8b2w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.214 23.361l5.607-1.724l4.205 13.079l-1.724 2.692l-3.911-.463zM39.513 42.37l-.86-2.298s-.59-.407-1.136-.365l-.435-1.472s-.853-.037-2.018.463a3.35 3.35 0 0 0-1.458 1.22l.462 1.667");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="lesps8d5n"/><path class="dj10qsbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:omron-connect" /></template>
<style>
.dj10qsbck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.77 32.745h1.906c1.051 0 1.904.853 1.904 1.904v3.143M9.5 34.65a1.905 1.905 0 1 1 3.81 0v1.237a1.905 1.905 0 1 1-3.81 0zm19.73 0a1.905 1.905 0 1 1 3.808 0v1.237a1.905 1.905 0 1 1-3.809 0zm9.172-20.975V18.7c0 .466.378.844.845.844h.253m-1.984-4.476h1.773m-27.634 3.625a1.689 1.689 0 0 1-3.155-.838v-1.098a1.688 1.688 0 0 1 3.153-.841m24.648 2.777a1.689 1.689 0 0 1-3.155-.838v-1.098a1.69 1.69 0 0 1 3.154-.841m-9.766 3.627v-2.786a1.689 1.689 0 1 0-3.377 0m0 2.786v-4.475m-1.736 4.475v-2.786a1.689 1.689 0 1 0-3.377 0m0 2.786v-4.475m13.264 3.622a1.689 1.689 0 0 1-3.156-.837v-1.096a1.689 1.689 0 1 1 3.377 0v.549h-3.377m-15.079-.549a1.689 1.689 0 1 1 3.377 0v1.097a1.689 1.689 0 1 1-3.377 0zM5.5 28h37");
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

.lesps8d5n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.233 37.792v-5.047h1.652c.934 0 1.691.759 1.691 1.695s-.757 1.695-1.691 1.695h-1.652m1.652 0l1.652 1.656m7.153.001v-5.047h1.906c1.051 0 1.904.853 1.904 1.904v3.143m-23.538 0v-5.047h3.809v5.047");
}

</style>

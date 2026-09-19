<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="lesps8d5n"/><path class="x2b_t7ely"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:omron-connect" /></template>
<style>
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

.x2b_t7ely {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.77 32.745h1.906c1.051 0 1.904.853 1.904 1.904v3.143M9.5 34.65a1.905 1.905 0 1 1 3.81 0v1.237a1.905 1.905 0 1 1-3.81 0zm19.73 0a1.905 1.905 0 1 1 3.808 0v1.237a1.905 1.905 0 1 1-3.809 0zm9.172-20.975V18.7c0 .466.378.844.845.844h.253m-1.984-4.476h1.773m-27.634 3.625c-.291.508-.839.85-1.466.85h0A1.69 1.69 0 0 1 8.5 17.854v-1.097c0-.933.756-1.689 1.689-1.689h0c.626 0 1.173.341 1.464.848m24.648 2.777c-.29.508-.838.85-1.466.85h0a1.69 1.69 0 0 1-1.688-1.689v-1.097c0-.933.756-1.689 1.688-1.689h0c.627 0 1.173.341 1.465.848m-9.766 3.627v-2.786c0-.933-.756-1.689-1.688-1.689h0c-.933 0-1.689.756-1.689 1.689m0 2.786v-4.475m-1.736 4.475v-2.786c0-.933-.756-1.689-1.689-1.689h0c-.932 0-1.688.756-1.688 1.689m0 2.786v-4.475m13.264 3.622c-.291.51-.84.853-1.468.853h0a1.69 1.69 0 0 1-1.688-1.689v-1.097c0-.933.756-1.689 1.688-1.689h0c.933 0 1.689.756 1.689 1.689v.548h-3.377m-15.079-.548a1.689 1.689 0 1 1 3.377 0v1.097a1.689 1.689 0 1 1-3.377 0zM5.5 28h37");
}

</style>

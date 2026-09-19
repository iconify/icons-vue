<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="tl36drbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-tele2" /></template>
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

.tl36drbzf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.229 19.697v8.494l3.753.147m-8.932-.352l3.392.134m-3.392-8.214l3.392-.137m-3.392 4.177l2.186-.001m-2.186-4.039v8.08m10.864.429l4.172.164m-4.172-9.11l4.172-.168m-4.172 4.641l2.685-.001m-2.685-4.472v8.946M9.5 20.204l4.051-.159m-2.068 7.878v-7.797m20.757 2.219c0-1.729 1.346-3.184 3.05-3.253c1.752-.07 3.21 1.346 3.21 3.166c0 .91-.33 1.774-.958 2.325c-1.299 1.143-5.302 4.08-5.302 4.08l6.26.247");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sz3f0-b_t"/><path class="iov95obsy"/><path class="v3e0i-cxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:successfactors" /></template>
<style>
.iov95obsy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.267 28.468a7.782 7.782 0 1 1 10.004 0");
}

.sz3f0-b_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.349 27.29c-11.17-10.955 4.397-28.4 15.878-15.668c10.76-12.732 26.58 4.544 15.505 15.668L24.227 42.866z");
}

.v3e0i-cxw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.939 28.032a6.485 6.485 0 0 1 7.888-10.28m11.444 10.716c.847.311 1.722.786 2.658 1.638m-12.662-1.638c-2.93 2.01-5.207 4.596-6.613 7.95m-2.715-8.386c-1.52.908-2.427 1.815-2.962 2.722");
}

</style>

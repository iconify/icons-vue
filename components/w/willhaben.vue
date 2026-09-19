<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j98an1bqd"/><path class="zka6-ck3p"/><path class="d667lpb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:willhaben" /></template>
<style>
.d667lpb3i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 24.51h-27a7.01 7.01 0 0 1-7.01-7.01h0a7.01 7.01 0 0 1 7.01-7.01h27");
}

.j98an1bqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4z");
}

.zka6-ck3p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.504 13.131l-2.184 8.738l-2.185-8.738l-2.184 8.738l-2.185-8.738m11.469 0v8.738m2.73-8.738v8.738h4.369m2.185-8.738v8.738h4.369m-14.02 2.641l-3.742 6.475m9.492-6.475l-5.128 8.92m-4.364-2.445c-2 3.464 2.33 5.964 4.33 2.5");
}

</style>

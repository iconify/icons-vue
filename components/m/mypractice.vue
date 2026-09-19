<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a_3-tcb5k"/><path class="oppppiwek"/><circle class="e41dfhbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mypractice" /></template>
<style>
.a_3-tcb5k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.992 42.49h9.236c2.449 0 5.903.22 7.5-1.377c1.598-1.598 1.34-5.014 1.34-7.463v-9.879c.235-3.907-.232-5.276-2.423-7.311L29.1 8.09c-1.447-1.149-3.286-2.585-5.12-2.59");
}

.e41dfhbsl {
  cx: 24px;
  cy: 27.782px;
  r: 6.606px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oppppiwek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.008 42.49h-9.236c-2.449 0-5.903.22-7.5-1.377c-1.598-1.598-1.34-5.014-1.34-7.463v-9.879c-.235-3.907.232-5.276 2.423-7.311L18.9 8.09c1.448-1.149 3.286-2.585 5.12-2.59m-6.626 15.747v21.212");
}

</style>

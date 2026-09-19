<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dca9t9blb"/><path class="x7m1tybrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:poc-bible-alt" /></template>
<style>
.dca9t9blb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.7 4.5h-2.3c-1.1 0-2 .9-2 2v35c0 1.1.9 2 2 2h2.3m0-39v39h24.9c1.1 0 2-.9 2-2v-35c0-1.1-.9-2-2-2z");
}

.x7m1tybrn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.164 8.156l2.702 8.83l7.703 2.08l-8.423 2.678l-1.982 18.1l-1.985-18.119l-8.439-2.659l7.703-2.08zM15.74 19.066h20.829M26.164 8.155v31.689");
}

</style>

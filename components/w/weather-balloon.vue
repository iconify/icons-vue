<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z29okt76d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:weather-balloon" /></template>
<style>
.z29okt76d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 15.913q-6.5-4.147-6.5-7.413q0-2.914 2.187-4.871Q9.037 1.75 12 1.75t5.063 1.879Q19.25 5.586 19.25 8.5q0 3.266-6.5 7.413v1.337H13q2.25 0 2.25 2.25v.5q0 2.25-2.25 2.25h-2q-2.25 0-2.25-2.25v-.5q0-2.25 2.25-2.25h.25z");
}

</style>

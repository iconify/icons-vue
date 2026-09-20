<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xwmti5b6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:warning-20-regular" /></template>
<style>
.xwmti5b6k {
  fill: currentColor;
  d: path("M7.37 3.556c1.14-2.074 4.12-2.074 5.259 0l5.496 10.005c1.098 1.999-.35 4.444-2.63 4.444H4.504c-2.281 0-3.727-2.445-2.629-4.444zm4.383.481c-.76-1.383-2.746-1.382-3.506 0L2.751 14.042c-.732 1.333.232 2.963 1.753 2.963h10.991c1.52 0 2.485-1.63 1.753-2.963zM10 12.75a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5m0-6.25a.5.5 0 0 1 .5.5v4a.5.5 0 0 1-1 0V7a.5.5 0 0 1 .5-.5");
}

</style>

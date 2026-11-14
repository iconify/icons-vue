<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m71u-2bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:personality-test" /></template>
<style>
.m71u-2bry {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 2.75h-11q-1.76 0-3.005 1.245T2.25 7v10q0 1.76 1.245 3.005T6.5 21.25h11q1.76 0 3.005-1.245T21.75 17V7q0-1.76-1.245-3.005T17.5 2.75m-11.75 7q0-2.929 2.568-3.571q2.012-.503 3.682.817q1.67-1.32 3.682-.817q2.568.642 2.568 3.571q0 2.787-2.695 3.355q.383.728.383 1.676q0 2.179-2.052 2.458q-1.159.266-1.886-.783q-.727 1.049-1.886.783q-2.051-.279-2.051-2.458q0-.948.382-1.676Q5.75 12.537 5.75 9.75");
}

</style>

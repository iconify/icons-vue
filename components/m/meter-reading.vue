<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsw6h1a5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:meter-reading" /></template>
<style>
.lsw6h1a5a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.625 2.25h-9.25q-2.123 0-3.624 1.501T2.25 7.375v9.25q0 2.123 1.501 3.624t3.624 1.501h5.292q-.167-.541-.167-1.25v-.379q0-1.449 1.024-2.474l3.312-3.311q1-1 2.414-1t2.414 1l.086.088V7.375q0-2.123-1.501-3.624T16.625 2.25M7.75 5.75h8.5q1.036 0 1.768.732t.732 1.768v2q0 1.036-.732 1.768t-1.768.732h-8.5q-1.036 0-1.768-.732T5.25 10.25v-2q0-2.5 2.5-2.5m6 14.75v-.379q0-.931.659-1.59l3.311-3.311q.633-.634 1.53-.634t1.53.634q.634.633.634 1.53t-.634 1.53l-3.311 3.311q-.659.659-1.59.659H15.5q-1.75 0-1.75-1.75m1.5 0v-.379q0-.31.219-.53l3.311-3.311q.195-.194.47-.194t.47.194q.194.195.194.47t-.194.47l-3.311 3.311q-.22.219-.53.219H15.5q-.25 0-.25-.25");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvp7zx-nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shipping-label-print" /></template>
<style>
.jvp7zx-nd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 2.75h6.5q1.036 0 1.768.732t.732 1.768v3.06q1.284.214 2.255 1.185Q21.25 10.74 21.25 12.5v2q0 1.76-1.245 3.005q-.971.971-2.255 1.185V19q0 2.25-2.25 2.25h-7q-2.25 0-2.25-2.25v-.31q-1.284-.214-2.255-1.185Q2.75 16.26 2.75 14.5v-2q0-1.76 1.245-3.005q.971-.971 2.255-1.185V5.25q0-2.5 2.5-2.5");
}

</style>

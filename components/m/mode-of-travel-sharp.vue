<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffjiit48n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mode-of-travel-sharp" /></template>
<style>
.ffjiit48n {
  fill: currentColor;
  d: path("M11.98 21q-.255 0-.441-.109q-.187-.108-.293-.333l-.155-.35q-.218-.506-.504-.955q-.287-.45-.63-.88q-.895-1.154-1.97-2.13t-1.835-2.235q-.604-.854-.878-1.876T5 10.025q0-2.921 2.024-4.973T11.975 3q3.246 0 5.251 2.516t2.005 5.857l2.465-2.446l.689.689l-3.654 3.653l-3.654-3.653l.683-.689l2.47 2.446q0-2.896-1.708-5.11Q14.814 4.05 11.975 4q-2.5 0-4.234 1.763Q6.006 7.525 6 10.025q0 .939.238 1.795t.737 1.64q.758 1.165 1.735 2.107q.976.943 1.832 2.016q.431.533.79 1.104q.359.57.643 1.186q.316-.646.691-1.232q.376-.585.819-1.13q-.233-.255-.371-.574t-.139-.687q0-.8.562-1.362t1.361-.561t1.362.562t.561 1.361t-.561 1.362t-1.362.561q-.182 0-.328-.029t-.29-.092q-.43.5-.791 1.038t-.623 1.118l-.156.35q-.106.211-.312.327q-.206.115-.417.115");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aisl35e5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:paste-style" /></template>
<style>
.aisl35e5b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 4.25h1.257q.122-2 2.243-2h.75q-1.243 0-2.121.879q-.879.878-.879 2.121q0 3 3 3h2.5q3 0 3-3q0-1.243-.879-2.121q-.878-.879-2.121-.879H14q.932 0 1.591.659q.569.569.647 1.341H17.5q2.75 0 2.75 2.75v12q0 2.75-2.75 2.75h-11q-2.75 0-2.75-2.75V7q0-2.75 2.75-2.75m4.25-.5q-.621 0-1.061.439q-.439.44-.439 1.061q0 1.5 1.5 1.5h2.5q1.5 0 1.5-1.5q0-.621-.439-1.061q-.44-.439-1.061-.439zm.699 6.241Q8.25 13.457 8.25 15.75q0 3.75 3.75 3.75t3.75-3.75q0-2.293-3.199-5.759q-.05-.054-.11-.097q-.059-.044-.127-.075q-.067-.031-.138-.048t-.146-.02q-.074-.003-.147.008q-.073.012-.142.037q-.069.026-.132.064t-.118.089q-.022.02-.042.042");
}

</style>

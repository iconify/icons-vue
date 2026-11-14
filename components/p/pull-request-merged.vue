<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_8fow-ld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pull-request-merged" /></template>
<style>
.v_8fow-ld {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 1.75q-2.75 0-2.75 2.75q0 2.397 2.09 2.705q.464 1.785 3.325 3.216Q11.25 11.714 11.25 13v3.81q-2 .345-2 2.69q0 2.75 2.75 2.75t2.75-2.75q0-2.345-2-2.69V13q0-1.286 2.585-2.579q2.861-1.431 3.325-3.216q2.09-.308 2.09-2.705q0-2.75-2.75-2.75T15.25 4.5q0 2.244 1.832 2.657q-.492.959-2.417 1.922q-1.815.907-2.665 1.957q-.85-1.05-2.665-1.957q-1.925-.963-2.417-1.922Q8.75 6.744 8.75 4.5q0-2.75-2.75-2.75");
}

</style>

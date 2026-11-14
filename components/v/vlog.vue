<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cswa7abmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:vlog" /></template>
<style>
.cswa7abmi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m18.569 5.281l-2.5 1.136h-.001q-.599.273-.926.721q-.066-.073-.137-.143Q13.76 5.75 12 5.75H6q-1.76 0-3.005 1.245T1.75 10v5q0 1.76 1.245 3.005T6 19.25h6q1.76 0 3.005-1.245T16.25 15v-.523q.077.026.158.048l2.499.682q1.074.293 1.959-.383q.884-.675.884-1.788V7.33q0-1.227-1.032-1.892t-2.149-.157M5.25 12.5q0-3.75 3.75-3.75t3.75 3.75T9 16.25T5.25 12.5");
}

</style>

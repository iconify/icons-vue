<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4j252b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-gift" /></template>
<style>
.x4j252b5c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 6.75h2.424q-.414-.35-.76-.781L6.4 5.95q-.831-1.109-.46-2.299Q6.378 2.25 8 2.25q2.442 0 4 3.232q1.558-3.232 4-3.232q1.622 0 2.06 1.401q.371 1.19-.46 2.299l-.014.019q-.346.431-.76.781h2.424q1.036 0 1.768.732t.732 1.768v1q0 1.036-.732 1.768q-.452.451-1.018.624v7.108q0 .828-.586 1.414T18 21.75H6q-.828 0-1.414-.586T4 19.75v-7.108q-.566-.173-1.018-.624q-.732-.732-.732-1.768v-1q0-2.5 2.5-2.5m.75 6h5.75v7.5H6q-.207 0-.354-.146q-.146-.147-.146-.354zm7.25 0v7.5H18q.207 0 .354-.146q.146-.147.146-.354v-7z");
}

</style>

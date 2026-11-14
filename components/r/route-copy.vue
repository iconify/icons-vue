<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocsw-je2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:route-copy" /></template>
<style>
.ocsw-je2c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 1.75Q7.75 1.75 7.75 4q0 1.603 1.142 2.064Q8.47 6.71 7.55 7.4q-2.3 1.725-2.3 3.6v4.299q-2.5.351-2.5 3.201q0 3.25 3.25 3.25t3.25-3.25q0-2.85-2.5-3.201V11q0-1.125 1.7-2.4q1.543-1.157 2.051-2.381Q12.25 5.984 12.25 4q0-2.25-2.25-2.25M15.75 4q0-2.25 2.25-2.25T20.25 4q0 1.984-1.749 2.219q-.508 1.224-2.051 2.381q-1.7 1.275-1.7 2.4v4.299q2.5.351 2.5 3.201q0 3.25-3.25 3.25t-3.25-3.25q0-2.85 2.5-3.201V11q0-1.875 2.3-3.6q.92-.69 1.342-1.336Q15.75 5.603 15.75 4");
}

</style>

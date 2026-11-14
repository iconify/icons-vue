<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b61hoi_sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-blood-donation" /></template>
<style>
.b61hoi_sn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.895 12.943l4.995 6.993q.072.102.174.174q.06.043.128.074q.067.03.139.047q.072.016.146.019q.073.002.146-.01t.142-.038q.069-.027.132-.066t.117-.089q.053-.051.096-.111l4.995-6.993q1.619-2.163 1.364-4.854q-.256-2.695-2.259-4.517T9.5 1.75T4.79 3.572T2.531 8.089q-.255 2.691 1.364 4.854M18.78 13.97Q22 17.189 22 18.5q0 3.75-3.75 3.75T14.5 18.5q0-1.311 3.22-4.53q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094M16 18.5q0-.62 2.25-2.932Q20.5 17.88 20.5 18.5q0 2.25-2.25 2.25T16 18.5");
}

</style>

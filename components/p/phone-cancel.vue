<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bud74bc4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:phone-cancel" /></template>
<style>
.bud74bc4x {
  fill: currentColor;
  d: path("M18.93 20q-2.528 0-5.184-1.266t-4.944-3.555q-2.27-2.288-3.536-4.935T4 5.07q0-.45.3-.76T5.05 4h2.473q.408 0 .721.257t.402.659L9.142 7.3q.07.42-.025.733t-.333.513L6.59 10.592q.616 1.117 1.361 2.076t1.59 1.817q.87.87 1.874 1.62q1.004.749 2.204 1.414l2.139-2.177q.244-.263.549-.357t.674-.023l2.103.43q.408.095.662.408t.254.715v2.435q0 .45-.31.75t-.76.3M15.113 9.596l-.708-.707l2.094-2.1l-2.094-2.075l.708-.714l2.1 2.1L19.287 4l.713.713l-2.08 2.076l2.08 2.1l-.713.707l-2.075-2.075z");
}

</style>

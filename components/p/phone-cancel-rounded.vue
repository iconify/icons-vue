<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-o0qlrjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:phone-cancel-rounded" /></template>
<style>
.j-o0qlrjq {
  fill: currentColor;
  d: path("M18.93 20q-2.528 0-5.184-1.266t-4.944-3.555q-2.27-2.288-3.536-4.935T4 5.07q0-.45.3-.76T5.05 4h2.473q.408 0 .721.257t.402.659L9.142 7.3q.07.42-.025.733t-.333.513L6.59 10.592q.616 1.117 1.361 2.076t1.59 1.817q.87.87 1.874 1.62q1.004.749 2.204 1.414l2.139-2.177q.244-.263.549-.357t.674-.023l2.103.43q.408.095.662.408t.254.715v2.435q0 .45-.31.75t-.76.3M17.213 7.521l-1.746 1.721q-.141.14-.342.153t-.366-.153q-.16-.16-.16-.354t.16-.353l1.74-1.746l-1.74-1.722q-.16-.14-.16-.341t.16-.366q.165-.166.357-.166q.19 0 .356.166l1.74 1.74l1.722-1.746q.14-.165.341-.165t.367.165t.165.357t-.166.356L17.92 6.79l1.726 1.746q.146.146.153.344t-.158.363q-.166.16-.354.163q-.189.003-.354-.163z");
}

</style>

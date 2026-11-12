<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="lk387obkc"/><path class="pek1alrpa"/><path class="mofxobcwr"/><path class="p_58s6ywe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:running-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lk387obkc {
  cx: 18.5px;
  cy: 4.5px;
  r: 2.5px;
}

.mofxobcwr {
  stroke-linejoin: round;
  d: path("M4 9.63632L5.43568 8.8206C7.69897 7.53463 8.91257 6.84509 10.1548 6.67356C10.3486 6.64679 10.5443 6.6276 10.7398 6.63626C10.8044 6.63913 10.8805 6.64449 10.9688 6.65365C13.0114 6.86567 14.6111 8.41672 15.7502 10.1253L15.8125 10.2188C16.5544 11.3316 17.8033 12 19.1407 12H21");
}

.p_58s6ywe {
  d: path("M13.9991 8.5L11.7784 11.2756L11.7784 11.2756C10.9419 12.321 10.5236 12.8438 10.457 13.413C10.4195 13.733 10.4598 14.0573 10.5746 14.3584C10.7788 14.8939 11.3124 15.2981 12.3797 16.1066C13.1926 16.7225 13.5991 17.0304 13.8745 17.4329C14.0316 17.6625 14.156 17.9129 14.2442 18.1767C14.3987 18.6394 14.3987 19.1493 14.3987 20.1692V21.9998");
}

.pek1alrpa {
  d: path("M9 17L7.99923 18.2009C7.262 19.0856 6.89338 19.5279 6.38945 19.764C5.88552 20 5.30973 20 4.15813 20H3");
}

</style>

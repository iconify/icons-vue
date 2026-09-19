<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n03-ghbgp"/><path class="vhwt7zoce"/><path class="lpe3n8bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:time-cop" /></template>
<style>
.lpe3n8bac {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.841 4.813c3.286 2.859 6.93 3.612 9.879 1.437a1.26 1.26 0 0 1 1.429-.002l2.96 1.928a1.305 1.305 0 0 1 .381 1.805a13 13 0 0 0-2.271 6.508c0 3.788 2.305 6.863 2.305 11.145c0 6.68-3.577 10.58-7.064 11.584C25.781 41.139 26.788 43.5 24 43.5s-1.781-2.36-8.46-4.282c-3.488-1.003-7.064-4.904-7.064-11.584c0-4.282 2.305-7.357 2.305-11.145A13 13 0 0 0 8.51 9.981a1.305 1.305 0 0 1 .382-1.804l2.96-1.929a1.26 1.26 0 0 1 1.428.002c2.949 2.175 6.593 1.421 9.879-1.437a1.29 1.29 0 0 1 1.682 0");
}

.n03-ghbgp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.333 17.934h11.334m-.683 0l-.592 1.125v.549a4.392 4.392 0 1 1-8.784 0v-.549l-.592-1.125m10.651 12.132H18.333");
}

.vhwt7zoce {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.016 30.066l.592-1.125v-.549a4.392 4.392 0 1 1 8.784 0v.549l.592 1.125");
}

</style>

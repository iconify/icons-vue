<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k-vc4pblu"/><path class="rgjrvcbns"/><path class="tn3klxy3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:running-low" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-vc4pblu {
  d: path("M2.5 5A5.25 2 0 1 0 13 5A5.25 2 0 1 0 2.5 5");
}

.rgjrvcbns {
  d: path("M2.5 5v14q0 .098.025.196t.076.194q.05.097.125.191t.174.184t.22.178q.121.086.265.168q.143.082.307.158q.163.076.346.145q.182.07.381.132q.2.062.414.117q.215.055.442.101q.228.046.466.084q.238.037.485.066q.247.028.5.048q.253.019.509.028q.257.01.515.01q.211 0 .422-.006q.211-.007.419-.02q.209-.013.414-.032q.206-.019.406-.045t.395-.057t.382-.069q.187-.037.366-.08t.348-.091t.327-.102t.305-.112t.28-.12q.134-.062.254-.129q.121-.066.226-.136q.106-.069.197-.142t.166-.148t.134-.153M13 16.595V5");
}

.tn3klxy3s {
  d: path("M2.5 16A5.25 2 0 0 0 13 16m5-1.5V21m-2.75-2.75L18 21l2.75-2.75");
}

</style>

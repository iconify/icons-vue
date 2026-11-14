<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vw3c8zbfz"/><path class="i8f30y5eh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:message-house" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i8f30y5eh {
  d: path("M7.5 20.5v-5q0-.098.019-.195t.057-.188t.093-.173t.124-.151t.151-.124t.173-.093t.188-.057t.195-.019h2q.192 0 .371.071q.179.072.318.204m.311 4.997v.728M15 14h5a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1h-3l-2 2v-2a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1");
}

.vw3c8zbfz {
  d: path("M11.83 20.5H6.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T5.12 20.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257v-6.164q0-.285.061-.563t.181-.537q.119-.258.291-.485t.389-.412l5.875-5.011q.088-.075.183-.142q.094-.067.194-.126t.205-.108t.214-.09q.108-.04.22-.07t.226-.051q.114-.02.23-.03q.115-.01.231-.01t.231.01t.23.03t.226.051t.22.07q.109.041.214.09t.205.108t.194.126t.183.142l5.875 5.011q.171.145.314.318q.143.172.256.366q.112.194.189.404q.078.21.119.431");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zbv873f3e"/><path class="eo94xbbxd"/><path class="tn3klxy3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:running-low" /></template>
<style>
.eo94xbbxd {
  d: path("M2.5 5v14q0 .098.025.196t.076.194q.05.097.125.191t.174.184t.22.178q.121.086.265.168q.143.082.307.158q.163.076.346.145q.182.07.381.132q.2.062.414.117q.215.055.442.101q.228.046.466.084q.238.037.485.066q.247.028.5.048q.253.019.509.028q.257.01.515.01q.205 0 .41-.006t.407-.018q.203-.013.403-.031q.199-.018.395-.042q.195-.024.385-.054q.189-.03.373-.065q.183-.035.358-.076t.342-.086q.166-.046.323-.097q.156-.05.302-.105t.28-.115t.255-.122t.23-.129t.202-.136t.174-.142q.079-.072.144-.146M13 16.595V5");
}

.tn3klxy3s {
  d: path("M2.5 16A5.25 2 0 0 0 13 16m5-1.5V21m-2.75-2.75L18 21l2.75-2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zbv873f3e {
  d: path("M2.5 5A5.25 2 0 1 0 13 5A5.25 2 0 1 0 2.5 5Z");
}

</style>

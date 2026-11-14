<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bn1de_bku"/><path class="g-qcd1bbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:settings-search" /></template>
<style>
.bn1de_bku {
  d: path("m8.314 3.755l.006-.084a.93.93 0 0 1 .93-.863a.93.93 0 0 1 .93.863l.006.084a1.39 1.39 0 0 0 .852 1.178a1.39 1.39 0 0 0 1.435-.23l.065-.056a.93.93 0 0 1 1.267.048a.93.93 0 0 1 .048 1.267l-.056.065a1.39 1.39 0 0 0-.23 1.435a1.39 1.39 0 0 0 1.178.852l.084.006a.93.93 0 0 1 .863.93a.93.93 0 0 1-.863.93l-.084.006a1.39 1.39 0 0 0-1.178.852a1.39 1.39 0 0 0 .23 1.435l.056.065a.93.93 0 0 1-.048 1.267a.93.93 0 0 1-1.267.048l-.065-.056a1.39 1.39 0 0 0-1.435-.23a1.39 1.39 0 0 0-.852 1.178l-.006.084a.93.93 0 0 1-.93.863a.93.93 0 0 1-.93-.863l-.006-.084a1.39 1.39 0 0 0-.852-1.178a1.39 1.39 0 0 0-1.435.23l-.065.056a.93.93 0 0 1-1.267-.048a.93.93 0 0 1-.048-1.267l.056-.065a1.39 1.39 0 0 0 .23-1.435a1.39 1.39 0 0 0-1.178-.852l-.084-.006a.93.93 0 0 1-.863-.93a.93.93 0 0 1 .863-.93l.084-.006a1.39 1.39 0 0 0 1.178-.852a1.39 1.39 0 0 0-.23-1.435l-.056-.065a.93.93 0 0 1 .048-1.267a.93.93 0 0 1 1.267-.048l.065.056a1.39 1.39 0 0 0 1.435.23a1.39 1.39 0 0 0 .852-1.178");
}

.g-qcd1bbr {
  d: path("M7.5 9.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M15 17.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m4.25 1.75L21 21");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

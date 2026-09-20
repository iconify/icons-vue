<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uk7acdcay"/><path class="b4de0eyhw"/><path class="lxtc-wp5b"/><path class="s-cqkabbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:socket-close-outline-bold" /></template>
<style>
.b4de0eyhw {
  d: path("M16 4h4v16h-4");
}

.lxtc-wp5b {
  d: path("m10 10 4 4");
}

.s-cqkabbd {
  d: path("m14 10 -4 4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uk7acdcay {
  d: path("M8 4H4v16h4");
}

</style>

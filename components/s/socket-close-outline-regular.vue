<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uk7acdcay"/><path class="b4de0eyhw"/><path class="lxtc-wp5b"/><path class="s-cqkabbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:socket-close-outline-regular" /></template>
<style>
.b4de0eyhw {
  d: path("M16 4h4v16h-4");
}

.lxtc-wp5b {
  d: path("m10 10 4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s-cqkabbd {
  d: path("m14 10 -4 4");
}

.uk7acdcay {
  d: path("M8 4H4v16h4");
}

</style>

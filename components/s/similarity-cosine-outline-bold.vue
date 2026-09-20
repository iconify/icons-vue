<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b5ic9acln"/><path class="ae0h5kb0o"/><path class="j-bgls0gn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:similarity-cosine-outline-bold" /></template>
<style>
.ae0h5kb0o {
  d: path("M9 15h6");
}

.b5ic9acln {
  d: path("m15 7 5 5 -8 8 -8 -8 5 -5");
}

.j-bgls0gn {
  d: path("m9 15 4.5 -4.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rpywjzbji"/><path class="qysv9g2ag"/><path class="r7xba0bis"/><path class="atcmxjbma"/><path class="p4idz7btn"/><path class="h6srt4n9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:type-check-duotone-bold" /></template>
<style>
.atcmxjbma {
  d: path("M4 5h12");
}

.h6srt4n9a {
  d: path("m14 15 3 3 5 -5");
}

.p4idz7btn {
  d: path("M10 5v10");
}

.qysv9g2ag {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 5v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r7xba0bis {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 15 3 3 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rpywjzbji {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 5h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>

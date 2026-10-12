<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="s1y66lvrm"/><path class="d9gv9881c"/><path class="j-9-a_bkc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nearby" /></template>
<style>
.d9gv9881c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.75h.01");
}

.j-9-a_bkc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 5.5a8.5 8.5 0 0 0 0 9m15.5-9a8.5 8.5 0 0 1 0 9M8.5 20.75h7");
}

.s1y66lvrm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 17c-.3 0-.55-.12-.75-.33C9 14.35 7.5 12.25 7.5 9.75a4.5 4.5 0 0 1 9 0c0 2.5-1.5 4.6-3.75 6.92c-.2.21-.45.33-.75.33");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

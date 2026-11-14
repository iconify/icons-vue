<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="md9o1691n"/><path class="z_qzmiqfi"/><path class="u8p78jm5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reply-all" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.md9o1691n {
  d: path("M8 11h6.5a5 5 0 0 1 5 5v3");
}

.u8p78jm5t {
  d: path("m8.5 6l-5 5l5 5");
}

.z_qzmiqfi {
  d: path("m13 6l-5 5l5 5");
}

</style>

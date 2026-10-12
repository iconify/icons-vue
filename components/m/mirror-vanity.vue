<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="w-arxbbnf"/><path class="jnuiqf9ak"/><path class="igfo6qxsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mirror-vanity" /></template>
<style>
.igfo6qxsi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.75 11.5l2.5-2.5M12 18.5v2.75m-4 0h8");
}

.jnuiqf9ak {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 5.5h.01m4.49 0h.01m4.49 0h.01M7.5 10.25h.01m8.99 0h.01M7.5 15h.01M12 15h.01m4.49 0h.01");
}

.w-arxbbnf {
  width: 14.5px;
  height: 15px;
  x: 4.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

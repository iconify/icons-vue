<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lszba4b2p"/><path class="u8_q54bsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:temperature-high" /></template>
<style>
.lszba4b2p {
  d: path("M4 6C4 3.7909 5.7909 2 8 2C10.2091 2 12 3.7909 12 6L12 11.101C12 11.3627 12.1026 11.614 12.2857 11.8009C13.3846 12.9224 14 14.4299 14 16C14 19.3137 11.3137 22 8 22C4.6863 22 2 19.3137 2 16C2 14.4299 2.6154 12.9224 3.7143 11.8009C3.8974 11.614 4 11.3627 4 11.101L4 6ZM8 16L8 7.5M22 5C22 6.6569 20.6569 8 19 8C17.3431 8 16 6.6569 16 5C16 3.3431 17.3431 2 19 2C20.6569 2 22 3.3431 22 5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u8_q54bsb {
  fill: currentColor;
  d: path("M9.5 16C9.5 16.8284 8.8284 17.5 8 17.5C7.1716 17.5 6.5 16.8284 6.5 16C6.5 15.1716 7.1716 14.5 8 14.5C8.8284 14.5 9.5 15.1716 9.5 16Z");
  stroke: none;
}

</style>

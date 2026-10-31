<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kfg1j9cvx"/><path class="jf-uovv_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:washing-machine" /></template>
<style>
.jf-uovv_h {
  fill: currentColor;
  d: path("M9 6C9 6.5523 8.5523 7 8 7C7.4477 7 7 6.5523 7 6C7 5.4477 7.4477 5 8 5C8.5523 5 9 5.4477 9 6Z");
  stroke: none;
}

.kfg1j9cvx {
  d: path("M7 2L17 2C18.6569 2 20 3.3431 20 5L20 19C20 20.6569 18.6569 22 17 22L7 22C5.3431 22 4 20.6569 4 19L4 5C4 3.3431 5.3431 2 7 2ZM16 14C16 16.2091 14.2091 18 12 18C9.7909 18 8 16.2091 8 14C8 11.7909 9.7909 10 12 10C14.2091 10 16 11.7909 16 14ZM12 6L16 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

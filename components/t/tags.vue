<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aulfjk6yh"/><path class="d5zm4bcvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tags" /></template>
<style>
.aulfjk6yh {
  d: path("M6 9C6 7.3431 7.3431 6 9 6L13.1716 6C13.702 6 14.2107 6.2107 14.5858 6.5858L21.4142 13.4142C22.1952 14.1952 22.1952 15.4616 21.4142 16.2426L16.2426 21.4142C15.4616 22.1952 14.1952 22.1952 13.4142 21.4142L6.5858 14.5858C6.2107 14.2107 6 13.702 6 13.1716ZM2 9L2 5C2 3.3431 3.3431 2 5 2L9 2");
}

.d5zm4bcvh {
  fill: currentColor;
  d: path("M12.5 11C12.5 11.8284 11.8284 12.5 11 12.5C10.1716 12.5 9.5 11.8284 9.5 11C9.5 10.1716 10.1716 9.5 11 9.5C11.8284 9.5 12.5 10.1716 12.5 11Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

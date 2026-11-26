<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="bj4_-zhpi"/><path class="jwuruxbqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-2-user-fill" /></template>
<style>
.bj4_-zhpi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2L19 2C21.2092 2 23 3.7908 23 6L23 14C23 16.2092 21.2092 18 19 18L5 18C2.7908 18 1 16.2092 1 14L1 6C1 3.7908 2.7908 2 5 2ZM14.1213 11.1213C14.6631 10.5795 15 9.8282 15 9C15 7.3431 13.6569 6 12 6C10.3431 6 9 7.3431 9 9C9 10.6569 10.3431 12 12 12C12.8282 12 13.5795 11.6631 14.1213 11.1213ZM7.1707 16L16.8293 16C16.4175 14.8348 15.3063 14 14 14L10 14C8.6937 14 7.5825 14.8348 7.1707 16Z");
  stroke: none;
}

.jwuruxbqn {
  d: path("M12 17L12 21M8 21L16 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

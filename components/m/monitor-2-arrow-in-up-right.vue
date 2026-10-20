<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_aba5e1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-2-arrow-in-up-right" /></template>
<style>
.i_aba5e1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3L5 3C3.3431 3 2 4.3431 2 6L2 14C2 15.6569 3.3431 17 5 17L19 17C20.6569 17 22 15.6569 22 14L22 13M12 17L12 21M8 21L16 21M16 3L21.4994 3C21.7756 3 22 3.2239 22 3.5L22 9M17 8L21.5 3.5");
}

</style>

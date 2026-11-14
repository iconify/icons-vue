<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zif96zz6d"/><path class="nh2v95bix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:points-expire" /></template>
<style>
.nh2v95bix {
  d: path("M20 14.5v1l-4 5v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zif96zz6d {
  d: path("M12.183 16.901L11 16.25l-5.143 2.829l1.101-5.766l-4.28-4.017l5.824-.734L11 3.25l2.498 5.312l5.824.734l-2.596 2.436m-2.353 6.373l-1.489-.819M15 14.5h6m-6 7h6m-5-7v1l4 5v1");
}

</style>

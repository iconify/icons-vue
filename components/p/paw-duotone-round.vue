<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="oh8fkitvx"/><path class="xx0r7gbdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paw-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.oh8fkitvx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15.172 10.2c1.056.899 1.774 2.102 2.617 3.186c.562.73 1.178 1.429 1.612 2.247c.392.73.6 1.538.599 2.367c0 .975-.467 1.803-1.284 2.329c-.802.515-1.778.671-2.716.671c-.855 0-1.591-.259-2.371-.572C13.108 20.22 12.57 20 12 20s-1.108.22-1.629.428C9.591 20.741 8.855 21 8 21c-.938 0-1.914-.156-2.716-.671C4.467 19.803 4 18.975 4 18c0-.829.205-1.637.599-2.367c.335-.631.779-1.193 1.222-1.75q.54-.675 1.043-1.379c.591-.817 1.192-1.646 1.964-2.304C9.735 9.43 10.805 9 12 9s2.265.43 3.172 1.2");
}

.xx0r7gbdh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10c2.5 0 3.6 2.2 5 4c1 1.3 2 2.3 2 4c0 1.3-1.2 2-3 2c-1.5 0-2.5-1-4-1s-2.5 1-4 1c-1.8 0-3-.7-3-2c0-1.7 1-2.7 2-4c1.4-1.8 2.5-4 5-4m-8 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m4-5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m4 5a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>

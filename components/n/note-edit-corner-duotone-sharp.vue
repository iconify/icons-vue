<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ajy7zz73r"/><path class="nnuwjxc-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-edit-corner-duotone-sharp" /></template>
<style>
.ajy7zz73r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 4v4H8v12H4V4Zm-7 17v-3l5-5l3 3l-5 5Z");
}

.ft5dv1b6b {
  fill: none;
}

.nnuwjxc-k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 20H4V4h16v4m-7 13v-3l5-5l3 3l-5 5Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="crb9vmbmz"/><path class="uld80q34v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rotate-ccw-square-sharp-duotone" /></template>
<style>
.crb9vmbmz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 10C15.552 10 16 10.45 16 11V22C16 22.55 15.552 23 15 23H4C3.448 23 3 22.55 3 22V11C3 10.45 3.448 10 4 10H15Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.uld80q34v {
  d: path("M14.003 1L15.37 2.46L14.526 3.25H19.999C20.551 3.25 20.999 3.7 20.999 4.25V10H18.999V5.25H14.528L15.398 6.07L14.031 7.52L11.315 4.98C11.146 4.82 11.015 4.45 10.988 4.2C11.03 3.99 11.166 3.66 11.315 3.52L14.003 1Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r6sdblw5a"/><path clip-rule="evenodd" class="k191mlbcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:minus-forward-slash-plus-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k191mlbcl {
  fill-rule: evenodd;
  d: path("M18.999 17H23V19H18.999L18.997 23L16.997 23L16.999 19H13V17H16.999L17 13H19L18.999 17ZM11 7H1V5H11V7Z");
}

.r6sdblw5a {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.118 2.15L5.521 23L3.883 21.85L18.48 1L20.118 2.15Z");
}

</style>

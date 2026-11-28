<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="cuhc0bb5y"/><path clip-rule="evenodd" class="ugl6v6bgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-pen-sharp-fill" /></template>
<style>
.cuhc0bb5y {
  d: path("M13 3H3V21L7 17H21V11");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ugl6v6bgo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.371 13.929L15.496 12.279C15.622 12.228 15.736 12.153 15.832 12.057L21.194 6.695C22.171 5.718 22.171 3.782 21.194 2.805C20.218 1.829 18.282 1.829 17.305 2.806L11.943 8.168C11.847 8.264 11.772 8.378 11.721 8.504L10.071 12.629C9.745 13.445 10.555 14.255 11.371 13.929Z");
  stroke: none;
}

</style>

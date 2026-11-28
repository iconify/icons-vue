<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kz9ufqblq"/><path clip-rule="evenodd" class="z5tvdhbcs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-off" /></template>
<style>
.kz9ufqblq {
  d: path("M4.172 14.172L2.586 12.586C2.211 12.211 2 11.702 2 11.172V5C2 3.343 3.343 2 5 2H11.172C11.702 2 12.211 2.211 12.586 2.586L14.172 4.172M17 7L21.414 11.414C22.195 12.195 22.195 13.462 21.414 14.243L14.243 21.414C13.462 22.195 12.195 22.195 11.414 21.414L7 17M22 2L2 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z5tvdhbcs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 8C9.5 8.828 8.828 9.5 8 9.5C7.172 9.5 6.5 8.828 6.5 8C6.5 7.172 7.172 6.5 8 6.5C8.828 6.5 9.5 7.172 9.5 8Z");
  stroke: none;
}

</style>

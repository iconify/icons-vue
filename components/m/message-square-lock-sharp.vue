<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd-gyobsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-lock-sharp" /></template>
<style>
.bd-gyobsz {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 9L21 3L3 3L3 21L7 17L11 17M14 16L21 16L21 21L14 21ZM15.5 16L15.5 14C15.5 12.8954 16.3954 12 17.5 12C18.6046 12 19.5 12.8954 19.5 14L19.5 16");
}

</style>

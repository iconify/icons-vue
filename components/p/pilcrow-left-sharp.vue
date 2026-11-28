<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bj5_z75gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pilcrow-left-sharp" /></template>
<style>
.bj5_z75gr {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 3L13 3C11.3431 3 10 4.3431 10 6C10 7.6569 11.3431 9 13 9L15 9M15 3L15 14M20 3L20 14M22 17L3 17M7.2929 12.7071L3 17L7.2929 21.2929");
}

</style>

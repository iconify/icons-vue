<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvpz1tbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:replace-sharp" /></template>
<style>
.jvpz1tbeu {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 4C7.6569 4 9 5.3431 9 7C9 8.6569 7.6569 10 6 10C4.3431 10 3 8.6569 3 7C3 5.3431 4.3431 4 6 4ZM12 7L21 7M17.7071 3.7071L21 7L17.7071 10.2929M15 14L21 14L21 20L15 20L15 14ZM12 17L3 17M6.2929 13.7071L3 17L6.2929 20.2929");
}

</style>

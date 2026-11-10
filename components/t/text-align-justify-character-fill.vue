<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc9epm6ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-align-justify-character-fill" /></template>
<style>
.kc9epm6ee {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 10L6.0862 3.6C6.4381 2.8 7.5619 2.8 7.9138 3.6L9.554 7M9.554 7L11 10M9.554 7H4.446M15 3H21M15 9H21M3 15H21M3 21H21");
}

</style>

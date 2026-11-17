<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyk392uym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-awning-open-sharp" /></template>
<style>
.kyk392uym {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 14H2.095L4 3H12M4 14H20M4 14V21M12 3H20L21.904 14H20M12 3V14M20 14V21M3.048 8.5H20.952M1 21H23");
}

</style>

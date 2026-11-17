<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kee7zojii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sun-rain" /></template>
<style>
.kee7zojii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 12C7.5 9.515 9.5147 7.5 12 7.5C14.4853 7.5 16.5 9.515 16.5 12M2 12H3.5M20.5 12H22M4.9289 4.929L5.9896 5.99M19.0711 4.929L18.0104 5.99M12 3.5V2M4 16H20M7 20L6 22M12 20L11 22M17 20L16 22");
}

</style>

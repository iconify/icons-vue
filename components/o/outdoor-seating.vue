<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyv8vgb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:outdoor-seating" /></template>
<style>
.dyv8vgb2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8L2.1758 8C2.106 8 2.0678 7.9186 2.1125 7.865L3.7991 5.8411C5.8273 3.4072 8.8318 2 12 2C15.1682 2 18.1727 3.4072 20.2009 5.8411L21.8875 7.865C21.9322 7.9186 21.894 8 21.8242 8ZM12 8L12 22M7 14L17 14M22 12L22 22M22 18L17.5 18C17.2239 18 17 18.2239 17 18.5L17 22M2 12L2 22M2 18L6.5 18C6.7761 18 7 18.2239 7 18.5L7 22");
}

</style>

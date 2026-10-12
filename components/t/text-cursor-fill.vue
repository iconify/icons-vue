<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1rcnw9pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-cursor-fill" /></template>
<style>
.u1rcnw9pp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4.25C11.5556 3.6875 10.1333 2 8 2M12 4.25C12.4444 3.6875 13.8667 2 16 2M12 4.25L12 19.75M12 19.75C12.4444 20.3125 13.8667 22 16 22M12 19.75C11.5556 20.3125 10.1333 22 8 22");
}

</style>

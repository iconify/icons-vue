<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9d4z_blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:timer-sharp" /></template>
<style>
.f9d4z_blx {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6C16.4183 6 20 9.5817 20 14C20 18.4183 16.4183 22 12 22C7.5817 22 4 18.4183 4 14C4 9.5817 7.5817 6 12 6ZM8 2L16 2M12 2L12 6M12 15L12 9M17.6569 8.3431L19.2929 6.7071");
}

</style>

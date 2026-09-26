<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kruiblb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mic-off" /></template>
<style>
.kruiblb1n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.3157 3.6589C9.8081 2.6753 10.8252 2 12 2L12 2C13.6569 2 15 3.3431 15 5L15 9.3431M13.5619 13.5619C13.1069 13.8398 12.5722 14 12 14L12 14C10.3431 14 9 12.6569 9 11L9 9M16.4246 16.4246C15.2187 17.4094 13.6783 18 12 18C8.134 18 5 14.866 5 11M12 18L12 22M8 22L16 22M2 2L22 22");
}

</style>

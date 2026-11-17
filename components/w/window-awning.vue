<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4rgfo8hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-awning" /></template>
<style>
.f4rgfo8hb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 9H12M4 9V15M4 9V4C4 3.448 4.448 3 5 3H19C19.552 3 20 3.448 20 4V9M12 9H20M12 9V15M4 15V21M4 15H12M20 9V15M12 15V21M12 15H20M20 15V21M2 21H4M4 21H12M12 21H20M20 21H22");
}

</style>

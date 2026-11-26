<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="veff9g5lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:peace" /></template>
<style>
.veff9g5lz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2C17.5228 2 22 6.4772 22 12C22 14.7614 20.8807 17.2614 19.0711 19.0711M12 2C6.4772 2 2 6.4772 2 12C2 14.7614 3.1193 17.2614 4.92895 19.0711M12 2V12M19.0711 19.0711C17.2614 20.8807 14.7614 22 12 22M19.0711 19.0711L12 12M19.0711 19.0711M12 22C9.2386 22 6.7386 20.8807 4.92895 19.0711M12 22V12M4.92895 19.0711L12 12M4.92895 19.0711");
}

</style>

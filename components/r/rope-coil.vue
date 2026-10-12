<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jss9xtkqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rope-coil" /></template>
<style>
.jss9xtkqu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.5 10.75l.05.36l-.01.38l-.09.39l-.16.37l-.24.35l-.3.32l-.37.26l-.42.2l-.46.12l-.49.04l-.51-.05l-.5-.14l-.48-.24l-.45-.32l-.38-.41l-.32-.49l-.23-.55l-.14-.59l-.03-.62l.08-.63l.2-.62l.31-.59l.42-.54l.52-.46l.6-.38l.68-.26l.72-.15l.75-.02l.76.12l.74.25l.7.39l.62.51l.54.62l.43.73l.3.8l.16.85l.01.88l-.15.89l-.31.85l-.46.81l-.61.72l-.73.61l-.84.49l-.93.33l-.98.17l-1.01-.01l-1.01-.18l-.98-.36l-.91-.54l-.81-.7l-.69-.84l-.54-.95l-.37-1.06L5 10.75l.02-1.14l.22-1.14l.41-1.09l.62-1.02l.78-.91l.95-.76l1.08-.6l1.18-.4l1.24-.19l1.27.03l1.27.25l1.21.47l1.12.69l1 .88l.84 1.06l.65 1.19l.44 1.31l.2 1.37m0 0c0 4.5-.5 7.5-2.25 10.5");
}

</style>

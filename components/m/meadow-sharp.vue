<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn8s4isfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:meadow-sharp" /></template>
<style>
.jn8s4isfq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25h18.5M8 21.25V12m8 9.25V9.75M4.25 21.25l-1-3.75m8.5 3.75l1-4m7.25 4l1-3.75m-5-1c1.25-2 2.75-2.75 4.5-2.5c-.5 1.75-2 2.75-4.5 2.5ZM8.3 7.02l.2.33l.3.51l.6.01h.38l.6.01l-.29.52l-.19.33l-.3.52l.3.52l.19.33l.29.53H9.4l-.6.01l-.3.51l-.2.33L8 12l-.3-.52l-.2-.33l-.3-.51l-.6-.01h-.98l.29-.53l.19-.33l.3-.52l-.3-.52l-.19-.33l-.29-.52l.6-.01h.38l.6-.01l.3-.51l.2-.33l.3-.52zm8.04-3.16l.24.43l.35.61l.69-.01l.49-.01h.7l-.35.6l-.25.42l-.36.6l.36.6l.25.42l.35.61l-.7-.01l-.49-.01l-.69-.01l-.35.61l-.24.43l-.34.61l-.34-.61l-.24-.43l-.34-.61l-.7.01l-.49.01l-.7.01l.35-.61l.25-.42l.36-.6l-.36-.6l-.25-.42l-.35-.6h.7l.49.01l.69.01l.35-.61l.24-.43l.34-.61z");
}

</style>

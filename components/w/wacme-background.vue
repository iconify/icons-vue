<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="hy7ce6-_y"/><path class="rhbs7xgtz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wacme-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hy7ce6-_y {
  fill: var(--svg-color--00a6fc, #00a6fc);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rhbs7xgtz {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.412 5.412a1.411 1.411 0 1 1-2.822 0a1.411 1.411 0 0 1 2.822 0m-7.53 4.705a1.412 1.412 0 1 0 0-2.823a1.412 1.412 0 0 0 0 2.823m0 6.588a1.412 1.412 0 1 0 0-2.823a1.412 1.412 0 0 0 0 2.823M12 20a1.412 1.412 0 1 0 0-2.823A1.412 1.412 0 0 0 12 20m6.118-3.295a1.412 1.412 0 1 0 0-2.823a1.412 1.412 0 0 0 0 2.823m0-6.588a1.412 1.412 0 1 0 0-2.823a1.412 1.412 0 0 0 0 2.823M12 13.411a1.412 1.412 0 1 0 0-2.823a1.412 1.412 0 0 0 0 2.823m2.32-1.821a2.3 2.3 0 0 0-.353-.88l2.277-1.242c.057.334.156.518.452.828zm-.466 1.854c.193-.244.339-.531.423-.842l2.386 1.087c-.301.283-.381.47-.386.857zm-2.325.862c.31.063.63.063.941 0v2.635a1.13 1.13 0 0 0-.941 0zm-1.798-1.68c.085.31.236.593.424.837l-2.15 1.294c-.024-.367-.16-.536-.48-.809zm-.056-.989l-.033.061l-2.353-1.411c.33-.344.424-.518.48-.81L9.976 10.8a2.3 2.3 0 0 0-.301.842zm2.795-1.943a2.4 2.4 0 0 0-.941 0V7.059c.306.122.518.113.941 0z");
}

</style>

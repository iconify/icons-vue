<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxx30q7_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:piping-bag-sharp" /></template>
<style>
.oxx30q7_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 5.25l-.432-1.727L13.5 2.75M6 5.25h13.25l-.59 1.1l-4.07 7.55L14 15h-4l-.59-1.1l-4.07-7.55l-.59-1.1zM10.4 15H14l-.07.39l-.76 3.97l-.07.39l-.33-.23l-.44-.29L12 19l-.33.23l-.44.29l-.33.23l-.07-.39l-.76-3.97L10 15z");
}

</style>

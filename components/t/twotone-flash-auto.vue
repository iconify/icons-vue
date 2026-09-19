<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwk530dsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-flash-auto" /></template>
<style>
.vwk530dsp {
  fill: currentColor;
  d: path("M3 2v12h3v9l7-12H9l4-9zm14 0l-3.2 9h1.9l.7-2h3.2l.7 2h1.9L19 2zm-.15 5.65L18 4l1.15 3.65z");
}

</style>

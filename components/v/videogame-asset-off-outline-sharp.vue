<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7uk9nb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:videogame-asset-off-outline-sharp" /></template>
<style>
.d7uk9nb5e {
  fill: currentColor;
  d: path("M16.793 11.209q-.293-.291-.293-.707t.291-.709t.707-.293t.709.291t.293.707t-.291.709t-.707.293t-.709-.291M3 17V6.994h3.994L8 8H4v8h10.573L2.74 4.167l.714-.713l17.092 17.092l-.713.714l-4.26-4.26zm4.5-2.5v-2h-2v-1h2v-2h1v2h2v1h-2v2zM21 16.798h-.833L20 16.631V8h-9.188l-1-1H21zm-5.594-4.492");
}

</style>

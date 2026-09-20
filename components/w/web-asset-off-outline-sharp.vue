<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhhigpbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:web-asset-off-outline-sharp" /></template>
<style>
.jhhigpbtv {
  fill: currentColor;
  d: path("M21.104 22.53L17.573 19H3V5h2v1.427l-3.12-3.12l.714-.713l19.223 19.223zM4 18h12.573l-10-10H4zm17 .189l-1-1V8h-9.188l-3-3H21z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-fcjihgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wash-sharp" /></template>
<style>
.l-fcjihgs {
  fill: currentColor;
  d: path("M18 21H3v-9.563l9.26-6l.894.97l-2.277 3.785H19v1h-6v2.27h8v1h-8v2.269h7v1h-7V20h5zM16.378 7.409q-.609-.61-.609-1.391q0-.7.46-1.58t1.54-2.15q1.081 1.27 1.54 2.15t.46 1.58q0 .78-.61 1.39q-.611.611-1.392.611t-1.389-.61");
}

</style>

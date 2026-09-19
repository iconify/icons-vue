<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p6crjil4f"/><path class="kg9e_3bbj"/><path class="pq63nzcfk"/><path class="zzk9musgl"/><path class="g9s6facrq"/><path class="i77w88bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:schildinext" /></template>
<style>
.g9s6facrq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.95 15.298c.812 1.117-.25 3.272-2.373 4.814q0 0 0 0c-2.122 1.542-4.5 1.886-5.312.77c-.811-1.118.251-3.273 2.373-4.815q0 0 0 0c2.123-1.542 4.5-1.886 5.312-.77M7.516 33.433c2.856-.956 8.468-1.763 12.551-2.76c9.032-2.104 12.33-5.26 12.546-8.914c.86-5.646 2.026-7.86 5.126-7.03c8.977 3.313 3.213 11.556-.7 8.741c-2.467-.091-3.629 8.859-4.956 9.623c-3.543-.63-6.768 3.32-10.037 3.32c-3.395-.06-7.068-3.222-14.53-2.98");
}

.i77w88bzz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.082 33.094l1.679 6.405h-5.577l-1.388-4.891m-10 .371l-2.365 4.88l-5.525-.27l3.381-5.857");
}

.kg9e_3bbj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.714 24.42L5.5 25.3l2.645 3.641l1.213-.881c-1.322-1.82 13.896-12.878 17.832-8.63l.588.809l1.618-1.176l-7.935-10.921l-1.618 1.175l.588.81");
}

.p6crjil4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.163 15.747c-3.181 1.143-5.942 3.243-7.017 5.703m18.441-1.8c.603.6 1.431 1.133 1.399 1.96c-1.198 4.749-14.155 7.997-20.516 8.058c-.636-.173-.736-.638-.719-1.168");
}

.pq63nzcfk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.476 10.127c1.09 1.683.81 4.37-1.735 6.421m-8.305 6.624c-2.476 1.685-3.218 1.88-3.678 1.247");
}

.zzk9musgl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.436 23.171c-3.015.33-4.526-1.561-3.44-4.305s4.39-5.378 7.518-5.996c3.128-.617 4.986.999 4.227 3.678");
}

</style>

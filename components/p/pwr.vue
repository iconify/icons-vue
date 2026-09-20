<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGq9DjubVY)" class="tpkwquv8g"/><path fill="url(#SVGxT9vPcqc)" class="i_vlsjbel"/><defs><linearGradient id="SVGq9DjubVY" x1="5.842" x2="21.373" y1="17.471" y2="13.118" gradientUnits="userSpaceOnUse"><stop class="nbg31vb5l"/><stop offset="1" class="uun36chmi"/></linearGradient><linearGradient id="SVGxT9vPcqc" x1="4.402" x2="19.594" y1="6.651" y2="6.932" gradientUnits="userSpaceOnUse"><stop class="o-nihpa-g"/><stop offset="1" class="vqzmg8bgt"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pwr" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i_vlsjbel {
  d: path("M4.74 17.324A9.003 9.003 0 1 1 20.27 8.44c-.518-.872-1.56-1.508-3.49-1.508H8.623L5.81 9.745h9.565V8.62l3.376 2.25l-3.376 2.251v-1.125H5.81z");
}

.nbg31vb5l {
  stop-color: var(--svg-color--4d4d4d, #4d4d4d);
}

.o-nihpa-g {
  stop-color: var(--svg-color--008cc4, #008cc4);
}

.tpkwquv8g {
  d: path("M11.998 20.999A9.004 9.004 0 0 0 20.65 9.515q.068.388.068.793c0 3.601-3.562 4.501-5.345 4.501H8.622l-.563 2.814H4.964a9 9 0 0 0 7.034 3.376");
}

.uun36chmi {
  stop-color: var(--svg-color--1a1a1a, #1a1a1a);
}

.vqzmg8bgt {
  stop-color: var(--svg-color--00a8f8, #00a8f8);
}

</style>

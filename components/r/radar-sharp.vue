<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ezs6ylqtu"/><path class="d-a_qsb5c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:radar-sharp" /></template>
<style>
.d-a_qsb5c {
  fill: currentColor;
  d: path("M13.5 12C13.5 12.8284 12.8284 13.5 12 13.5C11.1716 13.5 10.5 12.8284 10.5 12C10.5 11.1716 11.1716 10.5 12 10.5C12.8284 10.5 13.5 11.1716 13.5 12Z");
  stroke: none;
}

.ezs6ylqtu {
  d: path("M21.0729 7.7396L21.3207 8.3773C21.7697 9.5324 22 10.7608 22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2C14.6522 2 17.1957 3.0536 19.0711 4.9289L12 12M16.2426 7.7574C15.1174 6.6321 13.5913 6 12 6C8.6863 6 6 8.6863 6 12C6 15.3137 8.6863 18 12 18C15.2313 18 17.8823 15.441 17.9963 12.2117L18.0303 11.247");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ikrpzhbvp"/><path class="q-5wifgia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:video-2-two-tone" /></template>
<style>
.ikrpzhbvp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 5C16.6569 5 18 6.34312 18 8V8.38184L20.1055 7.3291C21.435 6.66456 22.9996 7.63177 23 9.11816V14.8828C22.9995 16.3691 21.435 17.3354 20.1055 16.6709L18 15.6182V16C18 17.6569 16.6569 19 15 19H4C2.34312 19 1 17.6569 1 16V8C1 6.34312 2.34312 5 4 5H15Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q-5wifgia {
  d: path("M4 6L15 6C16.1046 6 17 6.8954 17 8L17 16C17 17.1046 16.1046 18 15 18L4 18C2.8954 18 2 17.1046 2 16L2 8C2 6.8954 2.8954 6 4 6ZM17 10L20.5528 8.2236C21.2177 7.8912 22 8.3747 22 9.118L22 14.882C22 15.6253 21.2177 16.1088 20.5528 15.7764L17 14");
}

</style>

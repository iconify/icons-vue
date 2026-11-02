<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ccdd61bij"/><path class="de60b-sok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wolf-duotone-round" /></template>
<style>
.ccdd61bij {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m20.414 13l1.293 1.293a1 1 0 0 1-.336 1.635l-4.647 1.859l-.83 1.66c-1.17 2.339-3.922 3.348-6.179 1.845a4.8 4.8 0 0 1-1.609-1.845l-.83-1.66l-4.647-1.859a1 1 0 0 1-.336-1.635L3.586 13l-1.293-1.293a1 1 0 0 1 0-1.414l1-1C3.848 8.737 4 7.749 4 7V5c0-.898.572-1.928 1.521-2.089a1.34 1.34 0 0 1 1.186.382l2 2C9.263 5.848 10.251 6 11 6h2c.749 0 1.737-.152 2.293-.707l2-2c.31-.311.752-.456 1.186-.382C19.428 3.072 20 4.102 20 5v2c0 .749.152 1.737.707 2.293l1 1a1 1 0 0 1 0 1.414Z");
}

.de60b-sok {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m21 11l-2 2l2 2l-5 2l-1 2c-.613 1.226-1.774 2-3 2s-2.387-.774-3-2l-1-2l-5-2l2-2l-2-2l1-1c.64-.64 1-1.72 1-3V5c0-.738.631-1.369 1-1l2 2c.64.64 1.72 1 3 1h2c1.28 0 2.36-.36 3-1l2-2c.369-.369 1 .262 1 1v2c0 1.28.36 2.36 1 3zM9 11l1 1m5-1l-1 1m-2 6h.01");
}

.ft5dv1b6b {
  fill: none;
}

</style>

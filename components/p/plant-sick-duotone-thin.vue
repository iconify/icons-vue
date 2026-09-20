<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aaakc7r5n"/><path class="cssae_b2t"/><path class="l4e9mib8f"/><path class="n-0bvdyee"/><path class="vt7vyubju"/><path class="e49gfxbmn"/><path class="ip9t47bii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:plant-sick-duotone-thin" /></template>
<style>
.aaakc7r5n {
  fill: currentColor;
  d: path("M9 15v5h6v-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.cssae_b2t {
  fill: currentColor;
  d: path("M12 10c-4 0 -7 2 -7 5 4 0 7 -2 7 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.e49gfxbmn {
  d: path("M12 10c-4 0 -7 2 -7 5 4 0 7 -2 7 -5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ip9t47bii {
  d: path("M12 8c4 0 7 2 7 5 -4 0 -7 -2 -7 -5");
}

.l4e9mib8f {
  fill: currentColor;
  d: path("M12 8c4 0 7 2 7 5 -4 0 -7 -2 -7 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n-0bvdyee {
  d: path("M9 15v5h6v-5Z");
}

.vt7vyubju {
  d: path("M12 4v11");
}

</style>

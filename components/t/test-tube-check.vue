<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v9i8vqbvt"/><path class="mu53uccft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:test-tube-check" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mu53uccft {
  d: path("m9.48 10.28l5.31-5.31l4.24 4.24l-5.31 5.31Zm4.24-6.37l6.37 6.37");
}

.v9i8vqbvt {
  d: path("m9.48 10.28l-4.24 4.24a3 3 0 0 0 4.24 4.24l4.24-4.24Z");
}

</style>

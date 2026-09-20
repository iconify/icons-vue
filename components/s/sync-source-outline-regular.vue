<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b_3lf0wwh"/><path class="j6vltz2ns"/><path class="pi15tzbod"/><path class="mi_m6achy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sync-source-outline-regular" /></template>
<style>
.b_3lf0wwh {
  d: path("M2 8a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.j6vltz2ns {
  d: path("M5 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.mi_m6achy {
  d: path("m17 9 3 3 -3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pi15tzbod {
  d: path("M12 12h8");
}

</style>

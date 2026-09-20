<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="skbifdbcx"/><path class="p3hd3cb1e"/><path class="ndrpubcng"/><path class="nezeczbos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sql-agent-outline-regular" /></template>
<style>
.ndrpubcng {
  d: path("M12 15.5h10");
}

.nezeczbos {
  d: path("M17 15.5V21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p3hd3cb1e {
  d: path("M12 14a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2h-6a2 2 0 0 1 -2 -2Z");
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

</style>

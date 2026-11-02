<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pc6b4wb0y"/><path class="sryocgbkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:parrot-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pc6b4wb0y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7.526 4.008A6.06 6.06 0 0 1 12 2c.727 0 1.451.143 2.11.457C16.227 3.466 17 5.798 17 8v3c0 1.4.583 2.82 1.171 4.076c.22.469.452.933.683 1.396L21.8 20.4a1 1 0 0 1-.242 1.43a1 1 0 0 1-.801.14c-1.06-.265-2.086-.65-3.108-1.034c-.934-.35-1.871-.706-2.839-.953c-1.791-.248-3.468-.899-4.603-2.373l-.039-.055a16.6 16.6 0 0 1-1.462-2.661c-.335-.782-.608-1.608-.686-2.459l-.727-.728a2.6 2.6 0 0 0-.342-.291A2.13 2.13 0 0 1 5.79 12.82c-.374.175-.852.267-1.237.074c-.785-.392-1.391-1.091-1.806-1.853C2.239 10.109 2 9.059 2 8c0-1.365.709-2.449 1.879-3.118c1.099-.628 2.398-.832 3.647-.874");
}

.sryocgbkw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 5c1-1.3 2.5-2 4-2c2.5 0 4 2 4 5v3c0 2 1 4 2 6l3 4c-2-.5-4-1.5-6-2c-1.5-.2-3-.7-4-2c-1-1.5-2-3.5-2-5l-1-1m-2 8h5m0-2v2m1-12h.01M8 5C5 5 3 6 3 8s1 3.5 2 4c.5 0 1-.5 1-1c0-1 1-1 2 0q.75-3 0-6");
}

</style>

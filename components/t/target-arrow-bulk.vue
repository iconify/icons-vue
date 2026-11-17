<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l6s1pyb3f"/><path class="etiw_mb7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:target-arrow-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.etiw_mb7e {
  d: path("M16 6.586V3a1 1 0 0 1 2 0v1.586l2.293-2.293a.999.999 0 1 1 1.414 1.414L19.414 6H21a1 1 0 0 1 0 2h-3.586l-4.707 4.707a.999.999 0 1 1-1.414-1.414Zm5.214 9.307c-2.15 5.087-8.018 7.468-13.106 5.319S.637 13.195 2.786 8.107a9.9 9.9 0 0 1 2.143-3.178a9.9 9.9 0 0 1 3.178-2.143A9.9 9.9 0 0 1 12 2a1 1 0 0 1 0 2a7.9 7.9 0 0 0-3.114.628a8 8 0 0 0-2.543 1.715a8 8 0 0 0-2.194 7.194a7.99 7.99 0 0 0 4.737 5.835A8.005 8.005 0 0 0 20 12a1 1 0 0 1 2 0a9.9 9.9 0 0 1-.786 3.893m-3.686-1.557A6.001 6.001 0 1 1 12 6a1 1 0 0 1 0 2a4 4 0 0 0-3.696 2.471A4 4 0 1 0 16 12a1 1 0 0 1 2 0a5.9 5.9 0 0 1-.472 2.336");
}

.l6s1pyb3f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 3v8h8a1 1 0 0 1 1 1A10 10 0 1 1 12 2a1 1 0 0 1 1 1");
}

</style>

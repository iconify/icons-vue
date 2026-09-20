<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="af7iv3n-p"/><path class="iiquwwbvb"/><path class="jnf_2db5t"/><path class="owfn5sxxm"/><path class="pt-3kkb2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stock-buy-outline-regular" /></template>
<style>
.af7iv3n-p {
  d: path("M12 2v2.5");
}

.iiquwwbvb {
  d: path("M5 6.5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2V16a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.jnf_2db5t {
  d: path("M12 18v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.owfn5sxxm {
  d: path("M12 8v6");
}

.pt-3kkb2k {
  d: path("M9 11h6");
}

</style>

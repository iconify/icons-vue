<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="ny2uljfpp"/><path class="abcvlstdk"/><path class="iq8_1bc6r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:weekly-runs" /></template>
<style>
.abcvlstdk {
  d: path("M41.886 28.325s-9.89-1.6-16.007.072s-18.524.8-18.524.8");
}

.iq8_1bc6r {
  d: path("M42.54 31.735c1.469-1.204 1.96-5.368 1.96-7.41c0-1.815-.739-6.709-1.933-7.897c0 0-1.738-.737-2.641 0c-2.96 2.412-8.925 7.943-16.34 0c0 0-11.486 5.424-14.586 6.207c-5.32 1.344-5.5 2.68-5.5 4.437c0 5.626 6.59 4.902 10.985 4.663c2.423-.131 25.356.147 28.055 0M20.686 21.264L24 25.125m-6.637-2.689l2.308 2.69");
}

.ny2uljfpp {
  d: path("M42.54 31.735c1.469-1.204 1.96-5.368 1.96-7.41c0-1.815-.739-6.709-1.933-7.897c0 0-1.738-.737-2.641 0c-2.96 2.412-8.925 7.943-16.34 0c0 0-11.486 5.424-14.586 6.207c-5.32 1.344-5.5 2.68-5.5 4.437c0 5.626 6.59 4.902 10.985 4.663c2.423-.131 25.356.147 28.055 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

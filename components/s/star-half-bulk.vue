<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m5o0dfb5i"/><path class="ixg68j6we"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:star-half-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ixg68j6we {
  d: path("M22.141 9.01a1.001 1.001 0 0 1 .566 1.697l-4.636 4.636l.915 5.493a1 1 0 0 1-.392.968a1 1 0 0 1-1.041.09l-4.889-2.444l-.027-.013l-.637-.319l-5.553 2.776a1 1 0 0 1-1.041-.09a1 1 0 0 1-.392-.968l.915-5.493l-4.636-4.636a1.001 1.001 0 0 1 .566-1.697l6.481-.926l2.766-5.531v-.002l.005-.008l.001-.002a1 1 0 0 1 1.782.012l2.766 5.531Zm-8.035.437L12 5.236L9.894 9.447a1 1 0 0 1-.753.543l-5.02.717l3.586 3.586a1 1 0 0 1 .279.871l-.677 4.063l4.242-2.121h.002a1 1 0 0 1 .894 0l4.244 2.121l-.677-4.063a1 1 0 0 1 .279-.871l3.586-3.586l-5.02-.717a1 1 0 0 1-.753-.543");
}

.m5o0dfb5i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 3v15a1 1 0 0 1-.553.894l-6 3a1 1 0 0 1-1.041-.09a1 1 0 0 1-.392-.968l.915-5.493l-4.636-4.636a1.001 1.001 0 0 1 .566-1.697l6.481-.926l2.766-5.531A.998.998 0 0 1 13 3");
}

</style>

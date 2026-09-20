<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="bjc53bb5t"><path class="arovj1ana"/><path class="yg_akiqng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xet" /></template>
<style>
.arovj1ana {
  d: path("M8.963 4.125H3L8.26 12L3 19.875h5.963L14.576 12z");
}

.bjc53bb5t {
  fill: var(--svg-color--0681ff, #0681ff);
}

.yg_akiqng {
  d: path("m12.686 8.648l2.723-3.96h4.472L14.89 12l4.984 7.313h-4.489l-2.435-3.555l-.44.506l2.526 3.611H21L15.69 12L21 4.125h-5.963l-2.773 3.971z");
}

</style>

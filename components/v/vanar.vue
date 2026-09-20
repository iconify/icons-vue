<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n0xsq5brj"><path class="q_avukbnb"/><path class="x49vm3b-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vanar" /></template>
<style>
.n0xsq5brj {
  fill: var(--svg-color--03d9af, #03d9af);
}

.q_avukbnb {
  d: path("m14.248 20.1l2.25-4.052L9.75 3.9h-4.5L3 7.95h4.503zm4.5-8.101L21 7.949L18.749 3.9H14.25l-2.249 4.05H16.5z");
}

.x49vm3b-s {
  d: path("m16.5 7.95l2.249-4.05H14.25l-2.249 4.05zm-8.997 0L9.75 3.9h-4.5L3 7.95z");
}

</style>

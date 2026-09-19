<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_hywb8ib"/><path class="qxcb7v8hr"/><path class="qke_5h9bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-remove-shopping-cart" /></template>
<style>
.qke_5h9bj {
  fill: currentColor;
  d: path("M20 4H7.12l2 2h9.19l-2.76 5h-1.44l1.94 1.94c.54-.14.99-.49 1.25-.97l3.58-6.49C21.25 4.82 20.76 4 20 4M7 18c-1.1 0-1.99.9-1.99 2S5.9 22 7 22s2-.9 2-2s-.9-2-2-2");
}

.qxcb7v8hr {
  fill: currentColor;
  d: path("M18.31 6H9.12l4.99 5h1.44z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.r_hywb8ib {
  fill: currentColor;
  d: path("M1.41 1.13L0 2.54l4.39 4.39l2.21 4.66l-1.35 2.45c-.16.28-.25.61-.25.96c0 1.1.9 2 2 2h7.46l1.38 1.38A1.997 1.997 0 0 0 17 22c.67 0 1.26-.33 1.62-.84L21.46 24l1.41-1.41zM7 15l1.1-2h2.36l2 2z");
}

</style>

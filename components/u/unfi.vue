<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kz9rwukcv"/><path class="t0kupccuc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:unfi" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kz9rwukcv {
  fill: var(--svg-color--000, #000);
  d: path("M6.753 7.363h6.13l3.753 3.753v6.13L12.884 21H6.752L3 17.247v-6.131zM7.429 9l-2.793 2.792v4.778l2.793 2.793h4.778L15 16.57v-4.778L12.207 9z");
}

.t0kupccuc {
  fill: var(--svg-color--38f997, #38f997);
  d: path("M11.117 3h6.13L21 6.753v6.13l-3.753 3.753h-6.13l-3.753-3.752V6.752zm.676 1.636L9 7.43v4.778L11.793 15h4.778l2.793-2.793V7.43L16.57 4.636z");
}

</style>

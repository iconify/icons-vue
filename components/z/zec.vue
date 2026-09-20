<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aen5bm2vw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zec" /></template>
<style>
.aen5bm2vw {
  fill: var(--svg-color--ecb244, #ecb244);
  d: path("M11.19 15.316h5.547v3.316H13.42V21h-2.844v-2.368H7.263v-3.01l5.521-6.938h-5.52V5.368h3.313V3h2.844v2.368h3.316v3.01z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nofom_b2p"/><path class="m9jpxfbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-local-post-office" /></template>
<style>
.m9jpxfbqg {
  fill: currentColor;
  d: path("M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 14H4V8l8 5l8-5zm-8-7L4 6h16z");
}

.nofom_b2p {
  fill: currentColor;
  d: path("m12 11l8-5H4zM4 8v10h16V8l-8 5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>

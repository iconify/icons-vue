<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="x6vb0-lkk"/><path class="mgpk_ybqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:stop-button" /></template>
<style>
.mgpk_ybqo {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M32 32h64v64H32z");
}

.x6vb0-lkk {
  fill: none;
  d: path("M0 0h128v128H0z");
}

</style>

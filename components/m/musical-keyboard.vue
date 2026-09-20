<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="lr26eqbon"/><path class="fo2s6k2fb"/><path class="s-ik6cclj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:musical-keyboard" /></template>
<style>
.fo2s6k2fb {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M19 33s0 1 1 1h5c1 0 1-1 1-1V5h-7zm9-28v28s0 1 1 1h4c1 0 1-1 1-1V5zM10 33s0 1 1 1h5c1 0 1-1 1-1V5h-7zm-8 0s0 1 1 1h4c1 0 1-1 1-1V5H2z");
}

.lr26eqbon {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M2 36s-2 0-2-2V2s0-2 2-2h32.031C36 0 36 2 36 2v32s0 2-2 2z");
}

.s-ik6cclj {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M30 23s0 1-1 1h-4c-1 0-1-1-1-1V3h6zm-9 0s0 1-1 1h-4c-1 0-1-1-1-1V3h6zm-9 0s0 1-1 1H7c-1 0-1-1-1-1V3h6z");
}

</style>

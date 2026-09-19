<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuglf7bgm"/><path class="hw-fzacmx"/><path class="be625c6pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-app-blocking" /></template>
<style>
.be625c6pp {
  fill: currentColor;
  d: path("M7 3h10v1H7zm0 17h10v1H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.hw-fzacmx {
  fill: currentColor;
  d: path("M17 18H7V6h10v1h2V3c0-1.1-.9-2-2-2H7c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2v-4h-2zM7 3h10v1H7zm10 18H7v-1h10z");
}

.kuglf7bgm {
  fill: currentColor;
  d: path("M18 8c-2.21 0-4 1.79-4 4s1.79 4 4 4s4-1.79 4-4s-1.79-4-4-4m-2.5 4A2.5 2.5 0 0 1 18 9.5c.42 0 .8.11 1.15.29l-3.36 3.36c-.18-.35-.29-.73-.29-1.15m2.5 2.5c-.42 0-.8-.11-1.15-.29l3.36-3.36c.18.35.29.73.29 1.15a2.5 2.5 0 0 1-2.5 2.5");
}

</style>

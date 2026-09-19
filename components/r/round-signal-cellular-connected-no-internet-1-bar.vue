<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djyw7_hwy"/><path class="tp3b3pqrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-signal-cellular-connected-no-internet-1-bar" /></template>
<style>
.djyw7_hwy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M22 8V4.41c0-.89-1.08-1.34-1.71-.71L3.71 20.29c-.63.63-.19 1.71.7 1.71H18V11c0-1.66 1.34-3 3-3z");
}

.tp3b3pqrg {
  fill: currentColor;
  d: path("M20 11v6c0 .55.45 1 1 1s1-.45 1-1v-6c0-.55-.45-1-1-1s-1 .45-1 1m-8 11V12l-8.29 8.29c-.63.63-.19 1.71.7 1.71zm8 0h2v-2h-2z");
}

</style>

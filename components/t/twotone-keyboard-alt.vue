<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcgz7kbfq"/><path class="b2ehi7b3k"/><path class="ck74abplg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-keyboard-alt" /></template>
<style>
.b2ehi7b3k {
  fill: currentColor;
  d: path("M21 4H3c-1.1 0-2 .9-2 2v13c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 15H3V6h18z");
}

.bcgz7kbfq {
  fill: currentColor;
  d: path("M3 19h18V6H3zM17 8h2v2h-2zm0 4h2v2h-2zm-4-4h2v2h-2zm0 4h2v2h-2zM9 8h2v2H9zm0 4h2v2H9zm-1 4h8v1H8zM5 8h2v2H5zm0 4h2v2H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ck74abplg {
  fill: currentColor;
  d: path("M9 8h2v2H9zM5 8h2v2H5zm3 8h8v1H8zm5-8h2v2h-2zm-4 4h2v2H9zm-4 0h2v2H5zm8 0h2v2h-2zm4-4h2v2h-2zm0 4h2v2h-2z");
}

</style>

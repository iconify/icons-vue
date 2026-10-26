<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="smg0_ctzs"><path class="scklfg04e"/><path class="vq2y90bbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:tailscale" /></template>
<style>
.scklfg04e {
  d: path("M32 160c17.673 0 32-14.327 32-32S49.673 96 32 96S0 110.327 0 128s14.327 32 32 32m96 0c17.673 0 32-14.327 32-32s-14.327-32-32-32s-32 14.327-32 32s14.327 32 32 32m0 96c17.673 0 32-14.327 32-32s-14.327-32-32-32s-32 14.327-32 32s14.327 32 32 32m96-96c17.673 0 32-14.327 32-32s-14.327-32-32-32s-32 14.327-32 32s14.327 32 32 32");
}

.smg0_ctzs {
  fill: var(--svg-color--232222, #232222);
}

.vq2y90bbj {
  d: path("M32 256c17.673 0 32-14.327 32-32s-14.327-32-32-32s-32 14.327-32 32s14.327 32 32 32m192 0c17.673 0 32-14.327 32-32s-14.327-32-32-32s-32 14.327-32 32s14.327 32 32 32M32 64c17.673 0 32-14.327 32-32S49.673 0 32 0S0 14.327 0 32s14.327 32 32 32m96 0c17.673 0 32-14.327 32-32S145.673 0 128 0S96 14.327 96 32s14.327 32 32 32m96 0c17.673 0 32-14.327 32-32S241.673 0 224 0s-32 14.327-32 32s14.327 32 32 32");
  opacity: var(--svg-opacity--0-4, 0.4);
}

</style>

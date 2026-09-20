<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":293};
const content = `<defs><linearGradient id="SVGGSBU6cxE" x1="50%" x2="49.855%" y1="7.896%" y2="93.343%"><stop offset="0%" class="y5fb0lpcu"/><stop offset="100%" class="ojj18acah"/></linearGradient></defs><path fill="url(#SVGGSBU6cxE)" class="ww-985bse"/><path class="sgxoehhjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:turbopack-icon" /></template>
<style>
.ojj18acah {
  stop-color: var(--svg-color--ff1e56, #ff1e56);
}

.sgxoehhjg {
  d: path("M46.4 108.369v84.128l81.6 46.64v-84.144zM128 53.441l-74.352 42.48l81.616 46.64l74.336-42.496z");
}

.ww-985bse {
  d: path("M128 0L46.16 46.768l.16 36.752L128 36.848l96 54.864L256 110V73.136zm-14.4 247.488L32 200.864V91.792l-.032-.016l-.176-36.8L0 73.136v146.288l81.68 46.672zM224 200.864v-92.56l32 18.288v92.832l-128 73.152l-31.888-18.224L128 255.76v-.048z");
}

.y5fb0lpcu {
  stop-color: var(--svg-color--0096ff, #0096ff);
}

</style>

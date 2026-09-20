<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k8swyrgte"/><path class="ufd3khtwb"/><path class="bobv80b5w"/><path class="hee5hnxll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ubiq" /></template>
<style>
.bobv80b5w {
  fill: var(--svg-color--333, #333);
  d: path("m19.65 9.024l-5.298-3.272v7.427z");
}

.ft5dv1b6b {
  fill: none;
}

.hee5hnxll {
  fill: var(--svg-color--494949, #494949);
  d: path("M11.486 21v-7.15l8.164-4.826v7.261z");
}

.k8swyrgte {
  fill: var(--svg-color--0ca579, #0ca579);
  d: path("m4.35 14.976l5.298 3.272v-7.427z");
}

.ufd3khtwb {
  fill: var(--svg-color--00ea90, #00ea90);
  d: path("M12.514 3v7.15L4.35 14.976V7.715z");
}

</style>

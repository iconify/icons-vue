<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sb_esbcjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-pin-corner-fill" /></template>
<style>
.sb_esbcjk {
  fill: currentColor;
  d: path("M4.393 5.053a5.001 5.001 0 1 1 9.213 3.896a5.001 5.001 0 0 1-9.213-3.896M20 12a1 1 0 0 1 0 2v1.586l.707.707c.182.182.326.398.424.635c.286.69.163 1.561-.549 1.932c-.18.093-.379.141-.582.14h-2v2a1 1 0 0 1-2 0v-2h-2a1.25 1.25 0 0 1-.582-.14c-.712-.371-.835-1.242-.549-1.932c.098-.237.242-.453.424-.635l.707-.707V14a1 1 0 0 1 0-2Zm-10 3v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1c0-1.862.731-3.636 2.05-4.95a6.9 6.9 0 0 1 2.225-1.499A6.9 6.9 0 0 1 9 14a1 1 0 0 1 1 1");
}

</style>

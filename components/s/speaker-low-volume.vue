<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="zzskni6tb"/><path class="r3cfn-biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:speaker-low-volume" /></template>
<style>
.r3cfn-biu {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("m15 26l8 8s1 1 2 1h1s1 0 1-1V2s0-1-1-1h-1c-1 0-2 1-2 1l-8 8z");
}

.zzskni6tb {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M9 10s-2 0-2 2v12c0 2 2 2 2 2h6l8 8s1 1 2 1h1s1 0 1-1V2s0-1-1-1h-1c-1 0-2 1-2 1l-8 8z");
}

</style>

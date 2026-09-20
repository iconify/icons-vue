<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="sampidniq"/><path class="ap5hrwbfl"/><path class="ltpzstbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:refactor" /></template>
<style>
.ap5hrwbfl {
  d: path("M51.2 89.6h80V51.2h-80v38.4zM32 147.2h99.149v-38.4H32v38.4zM51.2 208h80v-38.4h-80V208z");
  fill: var(--svg-color--fff, #FFF);
}

.ltpzstbqo {
  d: path("M131.2 89.6h48.103V51.2H131.2v38.4zm0 57.6H208v-38.4h-76.8v38.4zm0 60.8h96v-38.4h-96V208z");
  fill: var(--svg-color--8acfc2, #8ACFC2);
}

.sampidniq {
  d: path("M0 256h256V0H0v256z");
  fill: var(--svg-color--16a085, #16A085);
}

</style>

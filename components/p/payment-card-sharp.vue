<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbbue8b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:payment-card-sharp" /></template>
<style>
.sbbue8b2n {
  fill: currentColor;
  d: path("M2 20V4h20v16zm3-3h10L10 7H5zm8-8h6V7h-6z");
}

</style>

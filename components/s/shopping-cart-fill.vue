<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed09gt4wx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-cart-fill" /></template>
<style>
.ed09gt4wx {
  fill: currentColor;
  d: path("M5.917 5.598L6.618 7H19c.397 0 .779.127 1.1.36c.885.641 1.123 1.869.87 2.883l-1 4c-.178.713-.52 1.382-1.043 1.905c-.511.511-1.195.852-1.927.852h-7c-.699 0-1.336-.358-1.82-.842c-.506-.506-.866-1.14-1.116-1.807l-2.25-6h-.001l-.73-1.949c-.211-.415-.459-.824-.79-1.155c-.093-.093-.2-.198-.325-.248A.999.999 0 0 1 3 3c.699 0 1.336.358 1.82.842c.493.493.848 1.108 1.097 1.756M7 20a2 2 0 1 1 3.999-.001A2 2 0 0 1 7 20m9 0a2 2 0 1 1 3.999-.001A2 2 0 0 1 16 20");
}

</style>

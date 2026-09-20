<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdeeyub5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:replace-image-sharp" /></template>
<style>
.kdeeyub5f {
  fill: currentColor;
  d: path("M9 19h6l-1.975-2.575l-1.45 1.725l-.975-1.3zm-3 3V10h12v12zM3.5 8q.95-2.725 3.288-4.362T12 2q2.05 0 3.888.875T19 5.35V2h2v6h-6V6h1.9q-.975-.975-2.25-1.487T12 4Q9.975 4 8.262 5.075T5.676 8z");
}

</style>

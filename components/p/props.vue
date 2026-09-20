<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qrgjh2bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:props" /></template>
<style>
.qrgjh2bzk {
  fill: var(--svg-color--24d2fd, #24d2fd);
  fill-rule: evenodd;
  d: path("M8.062 8.062h5.625v-4.9C13.052 3.02 12.678 3 12 3a9 9 0 0 0-9 9c0 3.508 2.135 6.544 5.062 8.029zm7.875-4.091v11.966h-5.624v4.844c.635.141 1.009.219 1.687.219a9 9 0 0 0 9-9c0-3.507-2.135-6.544-5.063-8.03m-2.25 9.716h-3.374v-3.374h3.374z");
}

</style>

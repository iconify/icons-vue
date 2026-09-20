<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_7r2r0sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pln" /></template>
<style>
.w_7r2r0sa {
  fill: var(--svg-color--fc2952, #fc2952);
  d: path("M15.994 3H8.05L3.045 9.311L3 9.356l1.733 7.977l7.216 3.616L12 21l7.268-3.617L21 9.407zm1.254 11.2l2.21-2.785l-.956 4.399zm-9.821.837L10.65 19.1l-4.618-2.301zM9.4 4.08h5.248L12 7.596L9.402 4.074zM12 9.311l3.949 4.939l-3.95 4.99l-3.948-4.99zm-4.618 4.061L4.249 9.463l4.05-5.04l3.026 4.01zm9.191 1.716l1.395 1.71l-4.573 2.3zm3.223-5.574l-3.127 3.91l-3.949-4.99l3.037-4.01zM6.752 14.16l-1.249 1.564l-.962-4.354z");
}

</style>

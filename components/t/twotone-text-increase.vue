<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w725p37qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-text-increase" /></template>
<style>
.w725p37qx {
  fill: currentColor;
  d: path("M1.99 19h2.42l1.27-3.58h5.65L12.59 19h2.42L9.75 5h-2.5zm4.42-5.61L8.44 7.6h.12l2.03 5.79zM20 11h3v2h-3v3h-2v-3h-3v-2h3V8h2z");
}

</style>

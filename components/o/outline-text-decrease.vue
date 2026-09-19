<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti88hy8pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-text-decrease" /></template>
<style>
.ti88hy8pn {
  fill: currentColor;
  d: path("M.99 19h2.42l1.27-3.58h5.65L11.59 19h2.42L8.75 5h-2.5zm4.42-5.61L7.44 7.6h.12l2.03 5.79zM23 11v2h-8v-2z");
}

</style>

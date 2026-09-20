<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcjs53bfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:velas" /></template>
<style>
.rcjs53bfd {
  fill: var(--svg-color--0137c1, #0137c1);
  d: path("m15.375 9.975l-3.37 6.075l-3.38-6.075zM18.75 7.95l-13.5-.004L12.005 20.1zM3 3.9l1.125 2.03h15.75L21 3.9z");
}

</style>

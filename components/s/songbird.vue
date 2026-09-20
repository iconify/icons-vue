<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx-85lb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:songbird" /></template>
<style>
.yx-85lb8x {
  fill: var(--svg-color--e62058, #e62058);
  d: path("m5.7 21l4.082-7.426l-.743 6.414zm3.94-3.573l.505-4.417l5.41.71zm3.891-8.853l2.21 4.866l-5.447-.714zm1.155 1.826l2.738-1.37l-1.454 4.195zm-4.615 2.128L7.016 3l6.343 5.312zm6.909-1.312l.668-1.928l.652 3.144z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq-rj0kvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vtc" /></template>
<style>
.mq-rj0kvs {
  fill: var(--svg-color--35633e, #35633e);
  d: path("M4.264 11.264h4.234l2.18 2.952L8.59 17.2zm.157 1.63H3l.76-1.058l.646 1.058zm4.617 4.91l3.019-4.32l6.777-9.646c.85.77 1.581 1.663 2.166 2.65l-.007.127L11.631 19.9a.64.64 0 0 1-.8.2a.65.65 0 0 1-.23-.186z");
}

</style>

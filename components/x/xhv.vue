<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zts2x0z-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xhv" /></template>
<style>
.zts2x0z-y {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.813 8.794L6.374 13.98v5.332h2.812v-4.055l8.438-5.198V4.687h-2.812zm-1.688-.872V3h6.188v8.06l-8.438 5.074V21H4.688v-7.976zM4.688 3h6.187v4.922l-1.688.866v-4.1H6.375v5.833l-1.687.866zm8.437 13.129l1.688-.883v4.066h2.812v-5.81l1.688-.872V21h-6.188z");
}

</style>

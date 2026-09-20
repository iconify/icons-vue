<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":295};
const content = `<path class="s45234b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:valkey-icon" /></template>
<style>
.s45234b2n {
  fill: var(--svg-color--6983ff, #6983ff);
  d: path("M53.121 248.653L0 215.311V74.031L129.978 0L256 74.03v148.628l-128.283 72.335l-44.644-27.69v-67.815l-24.3-15.258v-76.857l70.075-40.124l68.38 40.124v80.247l-54.252 30.517v-32.212c16.388-6.216 27.69-22.04 27.69-41.254s-19.213-44.08-42.949-44.08s-42.949 19.78-42.949 44.08s11.868 35.038 27.691 41.254v61.598l15.258 9.607l94.94-53.686V92.114l-93.81-55.381l-96.635 55.382v104.547l20.344 12.998v38.428zm75.162-123.761c10.737 0 19.214 9.042 19.214 20.344s-8.477 20.345-19.214 20.345c-10.738 0-19.215-9.042-19.215-20.345s8.477-20.344 19.215-20.344");
}

</style>

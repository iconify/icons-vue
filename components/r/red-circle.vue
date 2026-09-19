<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="m9_k_0z3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:red-circle" /></template>
<style>
.m9_k_0z3k {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M57.55 14.452c9.697 14.11 6.11 33.405-8 43.1c-14.11 9.697-33.407 6.112-43.1-8c-9.687-14.11-6.111-33.407 8-43.1c14.11-9.697 33.406-6.11 43.1 8");
}

</style>

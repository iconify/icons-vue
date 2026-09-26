<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f7d4d647u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vision-pro-fill" /></template>
<style>
.f7d4d647u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 6L17 6C20.3137 6 23 8.6863 23 12C23 15.3137 20.3137 18 17 18C15.6593 18 14.4078 17.3283 13.6667 16.2111C13.2961 15.6525 12.6703 15.3166 12 15.3166C11.3297 15.3166 10.7039 15.6525 10.3333 16.2111C9.5922 17.3283 8.3407 18 7 18C3.6863 18 1 15.3137 1 12C1 8.6863 3.6863 6 7 6Z");
}

</style>

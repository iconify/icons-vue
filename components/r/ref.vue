<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b0vtzqbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ref" /></template>
<style>
.b0vtzqbrp {
  fill: var(--svg-color--f38f31, #f38f31);
  fill-rule: evenodd;
  d: path("M16.384 4.42H7.581L3 12l4.58 7.58h8.804L21 12zm-2.12 2.843H8.21v2.369h4.737L8.21 13.406v3.33l7.816-6.289zM11.6 14.676l1.938-1.584l3.2 3.643h-3.42z");
}

</style>

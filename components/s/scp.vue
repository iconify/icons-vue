<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gww0oyb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:scp" /></template>
<style>
.gww0oyb5q {
  fill: var(--svg-color--2074ee, #2074ee);
  fill-rule: evenodd;
  d: path("M15.938 10.313c0 2.306-1.632 3.937-3.938 3.937H8.062v-3.937c0-2.307 1.632-3.938 3.938-3.938s3.938 1.631 3.938 3.938m3.374 0A7.313 7.313 0 0 1 12 17.625H8.062V21H4.688V10.313a7.312 7.312 0 1 1 14.625 0");
}

</style>

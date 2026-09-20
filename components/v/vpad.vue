<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dqtu10b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vpad" /></template>
<style>
.dqtu10b0n {
  fill: var(--svg-color--68ffd2, #68ffd2);
  fill-rule: evenodd;
  d: path("m3 4.125l9 15.75l9-15.75zm4.972 2.812L9.384 9.57l-1.322 1.867h2.402L12 14.25l3.853-7.313z");
}

</style>

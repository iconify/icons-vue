<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re112eb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vlx" /></template>
<style>
.re112eb5k {
  d: path("M15.706 9.882L12 16.5L8.294 9.882zm3.176-2.118H5.118L12 19.941zM3 4.06l1.324 2.117h15.353L21 4.06z");
}

</style>

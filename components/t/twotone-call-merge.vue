<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-w76bnfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-call-merge" /></template>
<style>
.v-w76bnfx {
  fill: currentColor;
  d: path("m16.997 20.41l-3.408-3.407l1.4-1.407l3.41 3.408zM5.59 19L7 20.41l6-6V8h3.5L12 3.5L7.5 8H11v5.59z");
}

</style>

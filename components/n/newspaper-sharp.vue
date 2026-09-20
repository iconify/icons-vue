<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekqt4sbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:newspaper-sharp" /></template>
<style>
.ekqt4sbys {
  fill: currentColor;
  d: path("M2 21V3l1.675 1.675L5.325 3L7 4.675L8.675 3l1.65 1.675L12 3l1.675 1.675L15.325 3L17 4.675L18.675 3l1.65 1.675L22 3v18zm2-2h7v-6H4zm9 0h7v-2h-7zm0-4h7v-2h-7zm-9-4h16V8H4z");
}

</style>

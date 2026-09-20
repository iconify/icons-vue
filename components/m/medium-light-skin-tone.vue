<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ywjdr2bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:medium-light-skin-tone" /></template>
<style>
.ywjdr2bqg {
  fill: var(--svg-color--e0bb95, #e0bb95);
  d: path("M10 10h108v108H10z");
}

</style>

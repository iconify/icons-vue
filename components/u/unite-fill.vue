<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vojwx_bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:unite-fill" /></template>
<style>
.vojwx_bnb {
  fill: currentColor;
  d: path("M240 164a76 76 0 0 1-151.9 3.9a76 76 0 1 1 79.8-79.8A76.1 76.1 0 0 1 240 164");
}

</style>

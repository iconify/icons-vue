<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py5wsab5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:odin" /></template>
<style>
.py5wsab5t {
  fill: var(--svg-color--0c0c0c, #0c0c0c);
  d: path("M17.913 18.766A8.984 8.984 0 0 1 5.233 6.087l3.398 3.397v5.885h5.885zm.853-.853A8.984 8.984 0 0 0 6.087 5.233l3.397 3.398h5.885v5.885z");
}

</style>

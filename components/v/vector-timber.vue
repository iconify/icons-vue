<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":151};
const content = `<path class="evfz3ob1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:vector-timber" /></template>
<style>
.evfz3ob1k {
  fill: var(--svg-color--10e7ff, #10E7FF);
  d: path("m256 0l-91.429 150.862l-18.969-31.219L217.61 0H256ZM47.204 0l44.674 73.367L136.53 0h45.365L90.947 150.068L0 0h47.204Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="moacmzb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:yellow-circle" /></template>
<style>
.moacmzb6j {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--fdcb58, #fdcb58);
}

</style>

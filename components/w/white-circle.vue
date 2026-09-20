<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="kb8v6gg9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:white-circle" /></template>
<style>
.kb8v6gg9n {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--e6e7e8, #e6e7e8);
}

</style>

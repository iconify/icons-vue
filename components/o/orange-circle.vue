<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="y-jqxs3dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:orange-circle" /></template>
<style>
.y-jqxs3dx {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--f4900c, #f4900c);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zn4395msc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:small-blue-diamond" /></template>
<style>
.zn4395msc {
  fill: var(--svg-color--03a9f4, #03a9f4);
  d: path("M64 92.17c-.68 0-1.37-.26-1.89-.78L36.6 65.88a2.68 2.68 0 0 1 0-3.78l25.51-25.52c1-1 2.77-1 3.77 0L91.4 62.1c.5.5.78 1.18.78 1.89s-.28 1.39-.78 1.89L65.88 91.39c-.52.51-1.2.78-1.88.78");
}

</style>

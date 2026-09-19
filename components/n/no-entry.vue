<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="qm7pesb5s"/><path class="e5xzwot2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:no-entry" /></template>
<style>
.e5xzwot2c {
  fill: var(--svg-color--fff, #fff);
  d: path("M9 26h46v12H9z");
}

.qm7pesb5s {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ff5a79, #ff5a79);
}

</style>

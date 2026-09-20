<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szqu4ibwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:upi-pay-outline-sharp" /></template>
<style>
.szqu4ibwh {
  fill: currentColor;
  d: path("M11.5 14.692h.885v-2.076h3.5V9.308H11.5zm5.77 0h.884V9.308h-.885zm-4.885-2.961v-1.539H15v1.539zM5.73 14.692h4.385V9.308H9.23v4.5H6.616v-4.5H5.73zM3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>

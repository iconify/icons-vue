<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xicr1ib_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:screenshot-tablet-sharp" /></template>
<style>
.xicr1ib_p {
  fill: currentColor;
  d: path("M2 19V5h20v14zm3.5-1h13V6h-13zm8.423-1.384h3.193v-3.193h-.885v2.308h-2.308zm-7.038-6.039h.884V8.269h2.308v-.885H6.884z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb8yubbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-off-fill-sharp" /></template>
<style>
.wb8yubbia {
  fill: currentColor;
  d: path("M16.828 15.586L8.414 7.172l4.879-4.879A1 1 0 0 1 15 3v7h5a1.002 1.002 0 0 1 .707 1.707ZM2.707 4.293l17 17a.999.999 0 1 1-1.414 1.414L14 18.414l-3.293 3.293A1 1 0 0 1 9 21v-7H4a1.002 1.002 0 0 1-.707-1.707L5.586 10L1.293 5.707a.999.999 0 1 1 1.414-1.414");
}

</style>

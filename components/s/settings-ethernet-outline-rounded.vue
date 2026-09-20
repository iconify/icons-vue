<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds5z0ac_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-ethernet-outline-rounded" /></template>
<style>
.ds5z0ac_t {
  fill: currentColor;
  d: path("m20.189 12l-4.235-4.246q-.14-.14-.153-.341t.153-.367q.16-.16.354-.16t.353.16l4.389 4.389q.13.13.184.267q.052.137.052.298t-.052.298t-.184.268l-4.389 4.388q-.14.14-.34.153t-.367-.153q-.16-.16-.16-.354t.16-.354zM3.81 12l4.235 4.246q.14.14.153.342t-.153.366q-.16.16-.354.16t-.354-.16L2.95 12.565q-.13-.13-.184-.267q-.052-.136-.052-.298t.052-.298t.184-.267l4.389-4.389q.14-.14.34-.153t.367.153q.16.16.16.354t-.16.354zm3.64.549q-.22-.22-.22-.549t.22-.549t.549-.22t.549.22t.22.549t-.22.549t-.549.22t-.549-.22m4 0q-.22-.22-.22-.549t.22-.549t.549-.22t.549.22t.22.549t-.22.549t-.549.22t-.549-.22m4 0q-.22-.22-.22-.549t.22-.549t.549-.22t.549.22t.22.549t-.22.549t-.549.22t-.549-.22");
}

</style>

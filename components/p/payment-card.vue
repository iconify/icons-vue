<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7wktxtun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:payment-card" /></template>
<style>
.z7wktxtun {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.596q0-.69.463-1.153t1.152-.462h14.77q.69 0 1.152.462T21 6.596v10.789q0 .69-.463 1.153T19.385 19zm1.153-2.73h8.404L9.827 7.711H5.769zm7.5-7.097h4.962V7.711h-4.962z");
}

</style>

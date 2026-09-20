<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6wk-rb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:splitscreen-rounded" /></template>
<style>
.p6wk-rb0x {
  fill: currentColor;
  d: path("M5.616 10.635q-.691 0-1.153-.463T4 9.019V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v3.403q0 .69-.462 1.153t-1.153.463zm0 9.365q-.691 0-1.153-.462T4 18.384V15q0-.69.463-1.153t1.153-.462h12.769q.69 0 1.153.462T20 15v3.385q0 .69-.462 1.152T18.384 20z");
}

</style>

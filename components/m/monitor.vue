<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-_md438e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:monitor" /></template>
<style>
.p-_md438e {
  fill: currentColor;
  d: path("M7.192 20v-1.538l.77-.77H4.616q-.691 0-1.153-.462T3 16.077V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616v10.461q0 .69-.463 1.153t-1.153.462h-3.346l.77.77V20z");
}

</style>

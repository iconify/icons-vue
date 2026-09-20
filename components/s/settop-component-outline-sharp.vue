<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-53y8h9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settop-component-outline-sharp" /></template>
<style>
.z-53y8h9b {
  fill: currentColor;
  d: path("M3 16V8h18v8zm1-1h16V9H4zm1.5-2.5h4.923v-1H5.5zm7.692.308h1.616v-1.616h-1.616zm3 0h1.616v-1.616h-1.616zM4 15V9z");
}

</style>

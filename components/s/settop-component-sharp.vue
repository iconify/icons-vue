<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhst2qbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settop-component-sharp" /></template>
<style>
.nhst2qbna {
  fill: currentColor;
  d: path("M3 16V8h18v8zm2.5-3.5h4.923v-1H5.5zm7.692.308h1.616v-1.616h-1.616zm3 0h1.616v-1.616h-1.616z");
}

</style>

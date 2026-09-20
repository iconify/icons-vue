<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9gbh8bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:picture-in-picture-outline-sharp" /></template>
<style>
.d9gbh8bts {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1h16V6H4zm7.308-5.308H19V7h-7.692zm1-1V8H18v3.692zM4 18V6z");
}

</style>

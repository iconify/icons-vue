<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y7b8dez1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-down-right-fill" /></template>
<style>
.y7b8dez1j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 2C20.2091 2 22 3.79086 22 6V18C22 20.2091 20.2091 22 18 22H6C3.79086 22 2 20.2091 2 18V6C2 3.79086 3.79086 2 6 2H18ZM15 8C14.4477 8 14 8.44772 14 9V12.5859L9.70703 8.29297C9.31651 7.90244 8.68349 7.90244 8.29297 8.29297C7.90244 8.68349 7.90244 9.31651 8.29297 9.70703L12.5859 14H9C8.44772 14 8 14.4477 8 15C8 15.5523 8.44772 16 9 16H14.5C15.3284 16 16 15.3284 16 14.5V9C16 8.44772 15.5523 8 15 8Z");
}

</style>

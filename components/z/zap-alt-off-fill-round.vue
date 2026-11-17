<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu5ddikmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-alt-off-fill-round" /></template>
<style>
.xu5ddikmx {
  fill: currentColor;
  d: path("M15.328 14.086L7.471 6.228l1.087-2.446A3 3 0 0 1 11.3 2H15a2.162 2.162 0 0 1 1.876 3.233L14.861 8.76A.16.16 0 0 0 15 9h1a1.827 1.827 0 0 1 1.293 3.121ZM2.707 4.293l17 17a.999.999 0 1 1-1.414 1.414L12.5 16.914l-3.379 3.379a1.582 1.582 0 0 1-2.663-1.462l1.24-5.584A.202.202 0 0 0 7.5 13a1.974 1.974 0 0 1-1.805-2.777l.035-.078l-4.437-4.438a.999.999 0 1 1 1.414-1.414");
}

</style>

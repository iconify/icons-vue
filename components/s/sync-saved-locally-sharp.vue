<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl_nam--p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sync-saved-locally-sharp" /></template>
<style>
.cl_nam--p {
  fill: currentColor;
  d: path("m10.925 13.8l4.964-4.938l-.714-.714l-4.25 4.25L8.8 10.273l-.708.708zm-9.156 5.662v-1h20.462v1zm1.231-2v-13h18v13z");
}

</style>

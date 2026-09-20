<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmod78cxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:position-top-right-sharp" /></template>
<style>
.nmod78cxe {
  fill: currentColor;
  d: path("M9 10h9V7H9zM3 21V3h18v18z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nid-gh7jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:minimize-outline-sharp" /></template>
<style>
.nid-gh7jy {
  fill: currentColor;
  d: path("M6 21v-2h12v2z");
}

</style>

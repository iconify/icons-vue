<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzdozth7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-add" /></template>
<style>
.dzdozth7e {
  fill: currentColor;
  d: path("M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6z");
}

</style>

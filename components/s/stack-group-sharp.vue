<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6_jge8fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stack-group-sharp" /></template>
<style>
.w6_jge8fm {
  fill: currentColor;
  d: path("M8 22v-6H2V2h14v6h6v14z");
}

</style>

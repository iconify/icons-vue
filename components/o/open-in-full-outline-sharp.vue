<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic8hjjbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:open-in-full-outline-sharp" /></template>
<style>
.ic8hjjbxv {
  fill: currentColor;
  d: path("M3 21v-8h2v4.6L17.6 5H13V3h8v8h-2V6.4L6.4 19H11v2z");
}

</style>

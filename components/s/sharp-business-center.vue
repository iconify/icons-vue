<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8iqtlbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-business-center" /></template>
<style>
.y8iqtlbqg {
  fill: currentColor;
  d: path("M10 16v-1H3.01v6H21v-6h-7v1zm12-9h-6V5l-2-2h-4L8 5v2H2v7h8v-2h4v2h8zm-8 0h-4V5h4z");
}

</style>

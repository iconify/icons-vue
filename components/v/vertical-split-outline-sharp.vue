<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tez044jmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vertical-split-outline-sharp" /></template>
<style>
.tez044jmu {
  fill: currentColor;
  d: path("M4 14.346v-1h7v1zM4 18v-1h7v1zm0-7.346v-1h7v1zM4 7V6h7v1zm10 11V6h6v12zm1-1h4V7h-4zm2-5");
}

</style>

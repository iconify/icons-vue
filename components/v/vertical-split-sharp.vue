<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imj-v9bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vertical-split-sharp" /></template>
<style>
.imj-v9bph {
  fill: currentColor;
  d: path("M4 14.346v-1h7v1zM4 18v-1h7v1zm0-7.346v-1h7v1zM4 7V6h7v1zm10 11V6h6v12z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqhcpqbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:menu" /></template>
<style>
.cqhcpqbdr {
  fill: currentColor;
  d: path("M4 17.27v-1h16v1zm0-4.77v-1h16v1zm0-4.77v-1h16v1z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccuj2ebdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wallet-sharp" /></template>
<style>
.ccuj2ebdj {
  fill: currentColor;
  d: path("M2 20V4h20v16zM4 8h16V6H4zm11.775 6.075L20 10.525V10H4v1.225z");
}

</style>

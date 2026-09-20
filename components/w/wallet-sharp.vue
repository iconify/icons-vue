<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km3dhg6lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wallet-sharp" /></template>
<style>
.km3dhg6lg {
  fill: currentColor;
  d: path("M3 19V5h18v14zM4 8.5h16V6H4zm11.775 5.594L20 10.525V9.5H4v1.725z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnizpcb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:smart-display-outline-sharp" /></template>
<style>
.rnizpcb2q {
  fill: currentColor;
  d: path("M10 15.577L15.577 12L10 8.423zM3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdlieuclz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stat-0-outline" /></template>
<style>
.tdlieuclz {
  fill: currentColor;
  d: path("M12 17.577L6.423 12L12 6.423L17.577 12zm0-1.427L16.15 12L12 7.85L7.85 12zM12 12");
}

</style>

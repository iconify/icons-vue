<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn0c1yuif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stay-current-landscape-outline-sharp" /></template>
<style>
.jn0c1yuif {
  fill: currentColor;
  d: path("M1 19V5h22v14zm3-2V7H3v10zm2 0h12V7H6zm14 0h1V7h-1zM4 7H3zm16 0h1z");
}

</style>

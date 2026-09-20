<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg38sezga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:split-scene-right-outline-sharp" /></template>
<style>
.gg38sezga {
  fill: currentColor;
  d: path("M4 19V5h5.116v1H5v12h4.116v1zm7.5 2V3h1v2H20v14h-7.5v2zM5 18V6z");
}

</style>

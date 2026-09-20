<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw4ge6bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-rows-narrow" /></template>
<style>
.iw4ge6bvv {
  fill: currentColor;
  d: path("M3 15.5V13h18v2.5zM3 11V8.5h18V11zm0-4.5V4h18v2.5zM3 20v-2.5h18V20z");
}

</style>

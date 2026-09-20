<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgezz0zyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stay-primary-landscape-sharp" /></template>
<style>
.xgezz0zyv {
  fill: currentColor;
  d: path("M1 19V5h22v14Zm5-2h12V7H6Zm-3 0h1V7H3Zm17 0h1V7h-1ZM3 17V7h1v10Zm17 0V7h1v10Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix06gebmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:vertical-shades-sharp" /></template>
<style>
.ix06gebmg {
  fill: currentColor;
  d: path("M2 21v-2h2V3h16v16h2v2zm8-2h4V5h-4z");
}

</style>

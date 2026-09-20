<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ne6zcz2tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:position-bottom-left-sharp" /></template>
<style>
.ne6zcz2tb {
  fill: currentColor;
  d: path("M6 17h9v-3H6zm-3 4V3h18v18z");
}

</style>

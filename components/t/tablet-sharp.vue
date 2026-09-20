<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sebyljbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tablet-sharp" /></template>
<style>
.sebyljbld {
  fill: currentColor;
  d: path("M1 20V4h22v16zm5-2h12V6H6z");
}

</style>

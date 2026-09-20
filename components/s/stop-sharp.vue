<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocemagb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stop-sharp" /></template>
<style>
.ocemagb_f {
  fill: currentColor;
  d: path("M6 18V6h12v12z");
}

</style>

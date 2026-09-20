<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkl080bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stay-current-landscape-sharp" /></template>
<style>
.dkl080bfi {
  fill: currentColor;
  d: path("M1 19V5h22v14zm5-2h12V7H6z");
}

</style>

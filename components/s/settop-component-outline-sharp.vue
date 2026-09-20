<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzbiw1xsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:settop-component-outline-sharp" /></template>
<style>
.dzbiw1xsm {
  fill: currentColor;
  d: path("M2 17V7h20v10zm2-2h16V9H4zm1-2h6v-2H5zm8 0h2v-2h-2zm3 0h2v-2h-2zM4 15V9z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn7c8ibon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:monitor-outline-sharp" /></template>
<style>
.tn7c8ibon {
  fill: currentColor;
  d: path("M6 21v-2l1-1H2V3h20v15h-5l1 1v2zm-2-5h16V5H4zm0 0V5z");
}

</style>

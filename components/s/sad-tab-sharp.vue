<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohzrwtbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sad-tab-sharp" /></template>
<style>
.ohzrwtbkp {
  fill: currentColor;
  d: path("M7.5 16.5H9V15h6v1.5h1.5V15H15v-1.5H9V15H7.5ZM8 12h1.5V9.5H8Zm6.5 0H16V9.5h-1.5ZM2 20V4h8l2 2h10v14Z");
}

</style>

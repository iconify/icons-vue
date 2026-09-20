<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gaevpkbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:package-sharp" /></template>
<style>
.gaevpkbbp {
  fill: currentColor;
  d: path("M7 17h5v-2H7zm-4 4V3h18v18zM8 5v8l4-2l4 2V5z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewg8vebyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:splitscreen-vertical-add-outline-sharp" /></template>
<style>
.ewg8vebyg {
  fill: currentColor;
  d: path("M19 5h-4.025h.125h-.1zm-6-2h8v12h-2V5h-4v16h-2zM3 21V3h8v18zM9 5H5v14h4zm0 0H5zm10 18v-2h-2v-2h2v-2h2v2h2v2h-2v2z");
}

</style>

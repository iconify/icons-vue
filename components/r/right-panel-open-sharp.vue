<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbor5-b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:right-panel-open-sharp" /></template>
<style>
.bbor5-b8f {
  fill: currentColor;
  d: path("M11.5 16V8l-4 4zM5 19h9V5H5zm-2 2V3h18v18z");
}

</style>

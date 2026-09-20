<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwc8sqbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:top-panel-open-sharp" /></template>
<style>
.jwc8sqbzn {
  fill: currentColor;
  d: path("m12 16.5l4-4H8zM5 19h14v-9H5zm-2 2V3h18v18z");
}

</style>

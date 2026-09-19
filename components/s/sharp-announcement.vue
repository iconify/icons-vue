<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_mjssbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-announcement" /></template>
<style>
.j_mjssbjx {
  fill: currentColor;
  d: path("M22 2H2v20l4-4h16zm-9 9h-2V5h2zm0 4h-2v-2h2z");
}

</style>

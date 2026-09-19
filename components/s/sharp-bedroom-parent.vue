<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unlmzsb6d"/><path class="mqs5lbnim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-bedroom-parent" /></template>
<style>
.mqs5lbnim {
  fill: currentColor;
  d: path("M22 2H2v20h20zm-3 15h-1.5v-1.5h-11V17H5v-5l.65-.55V7H11c.37 0 .72.12 1 .32c.28-.2.63-.32 1-.32h5.35v4.45L19 12z");
}

.unlmzsb6d {
  fill: currentColor;
  d: path("M6.5 12h11v2h-11zm.75-3.5h4v2h-4zm5.5 0h4v2h-4z");
}

</style>

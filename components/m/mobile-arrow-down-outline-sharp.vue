<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysuk6j_eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-arrow-down-outline-sharp" /></template>
<style>
.ysuk6j_eh {
  fill: currentColor;
  d: path("m12 16l4-4l-1.4-1.4l-1.6 1.55V8h-2v4.15L9.4 10.6L8 12zm-7 7V1h14v5.1h1v4.8h-1V23zm2-2h10V3H7zm0 0V3z");
}

</style>

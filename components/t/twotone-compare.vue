<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0mvouz6n"/><path class="ypqsb7blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-compare" /></template>
<style>
.f0mvouz6n {
  fill: currentColor;
  d: path("M19 5h-5v7l5 6zm-9 13v-6l-5 6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ypqsb7blw {
  fill: currentColor;
  d: path("M19 3h-5v2h5v13l-5-6v9h5c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m-7-2h-2v2H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h5v2h2zm-2 17H5l5-6z");
}

</style>

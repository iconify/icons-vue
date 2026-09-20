<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv5mnbbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:new-label-outline-sharp" /></template>
<style>
.nv5mnbbwo {
  fill: currentColor;
  d: path("M12.27 19v-1h2.865l4.615-6l-4.615-6H4v4.616H3V5h12.635L21 12l-5.365 7zm-6.385 1v-3h-3v-1h3v-3h1v3h3v1h-3v3z");
}

</style>

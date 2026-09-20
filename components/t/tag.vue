<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvyw1e31h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tag" /></template>
<style>
.vvyw1e31h {
  fill: currentColor;
  d: path("m7.135 19.077l1-4H4.518l.25-1h3.616l1.038-4.154H5.808l.25-1h3.615l1-4h.962l-1 4h4.269l1-4h.962l-1 4h3.615l-.25 1h-3.616l-1.038 4.154h3.615l-.25 1h-3.615l-1 4h-.961l1-4h-4.27l-1 4zm2.211-5h4.27l1.038-4.154h-4.27z");
}

</style>

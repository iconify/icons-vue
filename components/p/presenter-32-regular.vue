<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t_fvd2b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presenter-32-regular" /></template>
<style>
.t_fvd2b2n {
  fill: currentColor;
  d: path("M27 16a1 1 0 0 1 .707 1.707L21 24.414v2.336A3.25 3.25 0 0 1 17.75 30h-3.5A3.25 3.25 0 0 1 11 26.75v-2.336l-6.707-6.707A1 1 0 0 1 5 16zm-14.293 7.293A1 1 0 0 1 13 24v2.75c0 .69.56 1.25 1.25 1.25h3.5c.69 0 1.25-.56 1.25-1.25V24a1 1 0 0 1 .293-.707L24.586 18H7.414zM18.25 11a3.25 3.25 0 0 1 3.25 3.25v.25h-2v-.25c0-.69-.56-1.25-1.25-1.25h-4.5c-.69 0-1.25.56-1.25 1.25v.25h-2v-.25A3.25 3.25 0 0 1 13.75 11zM16 2a3.75 3.75 0 1 1 0 7.5A3.75 3.75 0 0 1 16 2m0 2a1.75 1.75 0 1 0 0 3.5A1.75 1.75 0 0 0 16 4");
}

</style>

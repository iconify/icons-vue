<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="umuljfsuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tree-deciduous-28-filled" /></template>
<style>
.umuljfsuo {
  fill: currentColor;
  d: path("M9.21 5.562a5.002 5.002 0 0 1 9.58 0a5 5 0 0 1 4.021 6.303A5 5 0 0 1 20 21h-3v3a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2v-3H8a5 5 0 0 1-2.811-9.135A5 5 0 0 1 9.21 5.562M12.5 24a.5.5 0 0 0 .5.5h2a.5.5 0 0 0 .5-.5v-3h-3z");
}

</style>

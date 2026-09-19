<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm67x5emz"/><path class="rmiziqbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-vertical-shades" /></template>
<style>
.fm67x5emz {
  fill: currentColor;
  d: path("M6 5h2v14H6zm10 0h2v14h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.rmiziqbki {
  fill: currentColor;
  d: path("M20 19V3H4v16H2v2h20v-2zM8 19H6V5h2zm6 0h-4V5h4zm4 0h-2V5h2z");
}

</style>

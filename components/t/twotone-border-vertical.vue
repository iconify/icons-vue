<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="biw0pbfeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-border-vertical" /></template>
<style>
.biw0pbfeg {
  fill: currentColor;
  d: path("M7 3h2v2H7zm0 8h2v2H7zm0 8h2v2H7zm-4 0h2v2H3zM3 3h2v2H3zm0 8h2v2H3zm16-8h2v2h-2zM3 7h2v2H3zm8-4h2v18h-2zM3 15h2v2H3zm12-4h2v2h-2zm4 4h2v2h-2zm0-4h2v2h-2zm0-4h2v2h-2zm0 12h2v2h-2zm-4 0h2v2h-2zm0-16h2v2h-2z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-sw__b8p"/><path class="fd0mx7e0g"/><path class="e0uxti_oh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-dynamic-feed" /></template>
<style>
.b-sw__b8p {
  fill: currentColor;
  d: path("M12 7h8v4h-8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.e0uxti_oh {
  fill: currentColor;
  d: path("M20 3h-8c-1.1 0-2 .9-2 2v6c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 8h-8V7h8zM4 12H2v7c0 1.1.9 2 2 2h9v-2H4z");
}

.fd0mx7e0g {
  fill: currentColor;
  d: path("M8 8H6v7c0 1.1.9 2 2 2h9v-2H8z");
}

</style>

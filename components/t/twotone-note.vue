<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amiif-b9a"/><path class="ogzgctwmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-note" /></template>
<style>
.amiif-b9a {
  fill: currentColor;
  d: path("M15 6H4v12.01h16V11h-5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ogzgctwmp {
  fill: currentColor;
  d: path("M4 4c-1.1 0-2 .9-2 2v12.01c0 1.1.9 1.99 2 1.99h16c1.1 0 2-.9 2-2v-8l-6-6zm16 14.01H4V6h11v5h5z");
}

</style>

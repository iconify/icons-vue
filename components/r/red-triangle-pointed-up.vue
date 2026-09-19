<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="mu92qu32w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:red-triangle-pointed-up" /></template>
<style>
.mu92qu32w {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M62.46 55.1C53.353 38.468 44.245 21.84 35.138 5.204a3.576 3.576 0 0 0-6.325 0C19.706 21.836 10.596 38.464 1.491 55.1c-1.409 2.569.387 5.899 3.16 5.899h54.653c1.537 0 2.569-.828 3.108-1.952c.679-1.067.859-2.487.055-3.951");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rbw9qhbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:three-d-thin" /></template>
<style>
.rbw9qhbzb {
  fill: currentColor;
  d: path("M100 148a24 24 0 0 0-24-24a4 4 0 0 1-3.28-6.29L96.32 84H56a4 4 0 0 1 0-8h48a4 4 0 0 1 3.28 6.29L83.12 116.8a32 32 0 1 1-30 53.6a4 4 0 1 1 5.72-5.6A24 24 0 0 0 100 148m60-72a52 52 0 0 1 0 104h-24a4 4 0 0 1-4-4V80a4 4 0 0 1 4-4Zm0 8h-20v88h20a44 44 0 0 0 0-88M32 52h192a4 4 0 0 0 0-8H32a4 4 0 0 0 0 8m192 152H32a4 4 0 0 0 0 8h192a4 4 0 0 0 0-8");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tgf93dl9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:three-d-bold" /></template>
<style>
.tgf93dl9h {
  fill: currentColor;
  d: path("M88 148a16 16 0 0 0-16-16a12 12 0 0 1-9.83-18.88L77 92H52a12 12 0 0 1 0-24h48a12 12 0 0 1 9.83 18.88l-18.34 26.2A40 40 0 1 1 43.43 176a12 12 0 1 1 17.14-16.8A16 16 0 0 0 88 148m76-80a60 60 0 0 1 0 120h-24a12 12 0 0 1-12-12V80a12 12 0 0 1 12-12Zm0 24h-12v72h12a36 36 0 0 0 0-72M32 56h192a12 12 0 0 0 0-24H32a12 12 0 0 0 0 24m192 144H32a12 12 0 0 0 0 24h192a12 12 0 0 0 0-24");
}

</style>

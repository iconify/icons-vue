<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mnouy1plo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:piano-keys-light" /></template>
<style>
.mnouy1plo {
  fill: currentColor;
  d: path("M208 34H48a14 14 0 0 0-14 14v160a14 14 0 0 0 14 14h160a14 14 0 0 0 14-14V48a14 14 0 0 0-14-14M78 46h28v92H78Zm34 104a6 6 0 0 0 6-6V46h20v98a6 6 0 0 0 6 6h10v60h-52v-60Zm38-12V46h28v92ZM46 208V48a2 2 0 0 1 2-2h18v98a6 6 0 0 0 6 6h18v60H48a2 2 0 0 1-2-2m164 0a2 2 0 0 1-2 2h-42v-60h18a6 6 0 0 0 6-6V46h18a2 2 0 0 1 2 2Z");
}

</style>

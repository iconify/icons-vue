<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="t7zzz4baa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:white-medium-small-square" /></template>
<style>
.t7zzz4baa {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M40.03 40.03h47.95v47.95H40.03z");
}

</style>

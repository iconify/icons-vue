<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ccpke4r9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:organization-horizontal-16-regular" /></template>
<style>
.ccpke4r9m {
  fill: currentColor;
  d: path("M1 8a2.5 2.5 0 0 0 4.95.5H7v2.133C7 11.388 7.612 12 8.367 12h1.683a2.5 2.5 0 1 0 0-1H8.367A.367.367 0 0 1 8 10.633V5.366C8 5.164 8.164 5 8.367 5h1.683a2.5 2.5 0 1 0 0-1H8.367C7.612 4 7 4.612 7 5.366v2.135H5.95A2.5 2.5 0 0 0 1 8m2.5 1.5a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3m9 3.5a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3M11 4.5a1.5 1.5 0 1 1 3 0a1.5 1.5 0 0 1-3 0");
}

</style>

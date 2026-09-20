<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cq5o-ibnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:record-48-filled" /></template>
<style>
.cq5o-ibnd {
  fill: currentColor;
  d: path("M24 4C12.954 4 4 12.954 4 24s8.954 20 20 20s20-8.954 20-20S35.046 4 24 4m0 33c-7.18 0-13-5.82-13-13s5.82-13 13-13s13 5.82 13 13s-5.82 13-13 13");
}

</style>

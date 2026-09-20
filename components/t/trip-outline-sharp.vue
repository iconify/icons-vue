<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qixyqcb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:trip-outline-sharp" /></template>
<style>
.qixyqcb4q {
  fill: currentColor;
  d: path("M2 21V6h6V2h8v4h6v15zm8-15h4V4h-4zM6 8H4v11h2zm10 11V8H8v11zm2-11v11h2V8zm-6 5.5");
}

</style>

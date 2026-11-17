<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f69gr9b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:xing-fill-sharp" /></template>
<style>
.f69gr9b9v {
  fill: currentColor;
  d: path("m18.878 3.479l-5.733 10.51l3.723 6.515a1 1 0 1 1-1.736.992l-4-7a1 1 0 0 1-.01-.975l6-11a1 1 0 0 1 1.756.958M7.894 5.553l2 4a1 1 0 0 1 0 .894l-3 6a1 1 0 1 1-1.788-.894L7.882 10L6.106 6.447a1 1 0 1 1 1.788-.894");
}

</style>

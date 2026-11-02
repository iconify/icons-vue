<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulfxfjbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:path-fill-round" /></template>
<style>
.ulfxfjbnb {
  fill: currentColor;
  d: path("m15.968 9.446l-6.522 6.522a4 4 0 1 1-1.414-1.414l6.522-6.522a4 4 0 1 1 1.414 1.414m1.254-1.603a2.001 2.001 0 0 0 1.556-3.686a2 2 0 0 0-1.556 3.686m-9.808 8.743a2 2 0 1 0-2.828 2.828a2 2 0 0 0 2.828-2.828");
}

</style>

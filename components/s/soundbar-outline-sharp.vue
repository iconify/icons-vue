<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so2sj_b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:soundbar-outline-sharp" /></template>
<style>
.so2sj_b-a {
  fill: currentColor;
  d: path("M11 13h2V9h-2zm-6 6v-2h4v2zm10 0v-2h4v2zm-8-6q.825 0 1.413-.587T9 11t-.587-1.412T7 9t-1.412.588T5 11t.588 1.413T7 13m10 0q.825 0 1.413-.587T19 11t-.587-1.412T17 9t-1.412.588T15 11t.588 1.413T17 13M2 16V6h20v10zm2-2h16V8H4zm8-3");
}

</style>

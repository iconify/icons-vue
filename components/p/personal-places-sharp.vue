<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dczps7bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:personal-places-sharp" /></template>
<style>
.dczps7bvt {
  fill: currentColor;
  d: path("M6 21V4h9.75q.35 0 .65.163t.5.437L20 9l-3.1 4.4q-.2.275-.5.438t-.65.162H8v7z");
}

</style>

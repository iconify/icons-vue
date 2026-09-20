<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8pwv7xsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:perm-data-setting-outline" /></template>
<style>
.l8pwv7xsh {
  fill: currentColor;
  d: path("M2 22L22 2v9.65q-.475-.225-.975-.363T20 11.076v-4.25L6.825 20h5.425q.15.55.4 1.038t.55.962zm4.825-2L20 6.825l-6.587 6.587zM18 23l-.3-1.5q-.3-.125-.562-.262T16.6 20.9l-1.45.45l-1-1.7l1.15-1q-.05-.325-.05-.65t.05-.65l-1.15-1l1-1.7l1.45.45q.275-.2.538-.337t.562-.263L18 13h2l.3 1.5q.3.125.563.263t.537.337l1.45-.45l1 1.7l-1.15 1q.05.325.05.65t-.05.65l1.15 1l-1 1.7l-1.45-.45q-.275.2-.537.338t-.563.262L20 23zm2.413-3.588Q21 18.826 21 18t-.587-1.412T19 16t-1.412.588T17 18t.588 1.413T19 20t1.413-.587");
}

</style>

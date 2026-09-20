<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3b0vubgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:perm-data-setting" /></template>
<style>
.n3b0vubgv {
  fill: currentColor;
  d: path("M20.413 19.413Q21 18.825 21 18t-.587-1.412T19 16t-1.412.588T17 18t.588 1.413T19 20t1.413-.587M18 23l-.3-1.5q-.3-.125-.562-.262T16.6 20.9l-1.45.45l-1-1.7l1.15-1q-.05-.3-.05-.65t.05-.65l-1.15-1l1-1.7l1.45.45q.275-.2.538-.337t.562-.263L18 13h2l.3 1.5q.3.125.563.263t.537.337l1.45-.45l1 1.7l-1.15 1q.05.3.05.65t-.05.65l1.15 1l-1 1.7l-1.45-.45q-.275.2-.537.338t-.563.262L20 23zM2 22L22 2v9.65q-.65-.325-1.463-.488T19 11q-2.925 0-4.975 2.038T11.975 18q0 1.125.3 2.1T13.2 22z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d-fshwb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ngm" /></template>
<style>
.d-fshwb7c {
  fill: var(--svg-color--cbf6ec, #cbf6ec);
  fill-rule: evenodd;
  d: path("M3 12h1.626A7.31 7.31 0 0 0 12 19.312V21a9 9 0 0 1-9-9m9-9v1.687A7.313 7.313 0 0 1 19.25 12H21a9 9 0 0 0-9-9m2.79 10.896a3.375 3.375 0 0 1-6.12-1.334H7.5v-1.125h1.17a3.375 3.375 0 0 1 6.66 0h1.451l-.562 1.126h-6.11a1.968 1.968 0 0 0 3.427.675zm-4.68-2.459a1.97 1.97 0 0 1 3.774 0z");
}

</style>

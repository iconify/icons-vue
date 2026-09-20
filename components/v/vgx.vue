<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9foqwb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vgx" /></template>
<style>
.s9foqwb-y {
  fill: var(--svg-color--292375, #292375);
  d: path("M7.416 3H3.834a.234.234 0 0 0-.216.324l7.716 17.262a.705.705 0 0 0 1.284 0l7.764-17.262a.23.23 0 0 0-.106-.296a.23.23 0 0 0-.11-.028h-3.564a.7.7 0 0 0-.642.414l-3.966 8.628l-3.936-8.628A.69.69 0 0 0 7.416 3");
}

</style>

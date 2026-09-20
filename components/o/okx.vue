<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9yectbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:okx" /></template>
<style>
.p9yectbnp {
  d: path("M3 3h6v6H3zm12 6H9v6H3v6h6v-6h6v6h6v-6h-6zm0 0V3h6v6z");
}

</style>

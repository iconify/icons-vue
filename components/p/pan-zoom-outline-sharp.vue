<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9h9ewb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pan-zoom-outline-sharp" /></template>
<style>
.y9h9ewb1l {
  fill: currentColor;
  d: path("M3 21v-6h2v2.6l3.1-3.1l1.4 1.4L6.4 19H9v2zM15.9 9.5l-1.4-1.4L17.6 5H15V3h6v6h-2V6.4z");
}

</style>

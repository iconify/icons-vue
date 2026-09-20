<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxqhbubvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signpost-sharp" /></template>
<style>
.dxqhbubvv {
  fill: currentColor;
  d: path("M11 22v-4H6l-3-3l3-3h5v-2H4V4h7V2h2v2h5l3 3l-3 3h-5v2h7v6h-7v4z");
}

</style>

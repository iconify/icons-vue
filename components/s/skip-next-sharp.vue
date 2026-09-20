<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8q-hpbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:skip-next-sharp" /></template>
<style>
.u8q-hpbds {
  fill: currentColor;
  d: path("M16.5 18V6h2v12zm-11 0V6l9 6z");
}

</style>

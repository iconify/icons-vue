<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkb1f-bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vertical-shades-closed-sharp" /></template>
<style>
.fkb1f-bjh {
  fill: currentColor;
  d: path("M3 20v-1h2V4h14v15h2v1zm3-1h2.25V5H6zm3.25 0h2.25V5H9.25zm3.25 0h2.25V5H12.5zm3.25 0H18V5h-2.25z");
}

</style>

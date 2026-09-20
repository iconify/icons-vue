<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khzv6obrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:science-sharp" /></template>
<style>
.khzv6obrg {
  fill: currentColor;
  d: path("M5 21q-1.275 0-1.812-1.137t.262-2.113L9 11V5H7V3h10v2h-2v6l5.55 6.75q.8.975.263 2.113T19 21z");
}

</style>

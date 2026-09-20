<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8lrunbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:type-specimen-outline-sharp" /></template>
<style>
.n8lrunbyo {
  fill: currentColor;
  d: path("M9.8 14.5h1.6l.8-2.3h3.65l.8 2.3h1.55l-3.4-9h-1.6zm2.85-3.6l1.3-3.75h.1l1.3 3.75zM6 18V2h16v16zm2-2h12V4H8zm-6 6V6h2v14h14v2zM8 4v12z");
}

</style>

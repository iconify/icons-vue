<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amxb2nbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stack-hexagon-outline-sharp" /></template>
<style>
.amxb2nbzt {
  fill: currentColor;
  d: path("m14.5 13.5l3.5-2v-4l-3.5-2l-3.5 2v4zM12.825 19h5.425l.175 1.325l-14.725 1.8L1.85 7.2L5 6.85v2l-.9.125L5.45 19.9zM7 17V2h15v15zm2-2h11V4H9zm5.5-3.8l-1.5-.85v-1.7l1.5-.85l1.5.85v1.7z");
}

</style>

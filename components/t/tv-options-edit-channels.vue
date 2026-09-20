<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcc0cubip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tv-options-edit-channels" /></template>
<style>
.fcc0cubip {
  fill: currentColor;
  d: path("M3 15.385v-1.327h1.366v1.327zm0-3.404v-1.327h1.366v1.327zm0-3.385V7.29h1.366v1.307zm3.75 6.616v-1h2.942v1zm0-3.385v-1h11.558v1zm0-3.385v-1h11.558v1zM15.662 19l-3.385-3.384l.714-.714l2.67 2.671l5.285-5.284l.708.719z");
}

</style>

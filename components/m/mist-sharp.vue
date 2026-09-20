<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="we6sz4bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mist-sharp" /></template>
<style>
.we6sz4bgf {
  fill: currentColor;
  d: path("M3.5 18.5v-1h11v1zm14 0v-1h3v1zm-14-4v-1h3v1zm6 0v-1h11v1zm-6-4v-1h12v1zm15 0v-1h2v1zm-15-4v-1h6v1zm9 0v-1h8v1z");
}

</style>

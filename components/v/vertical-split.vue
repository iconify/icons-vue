<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f67_eacmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vertical-split" /></template>
<style>
.f67_eacmv {
  fill: currentColor;
  d: path("M4 14.346v-1h7v1zM4 18v-1h7v1zm0-7.346v-1h7v1zM4 7V6h7v1zm11.616 11q-.667 0-1.141-.475T14 16.386v-8.77q0-.666.475-1.14T15.615 6h2.77q.666 0 1.14.475T20 7.615v8.77q0 .666-.475 1.14t-1.14.475z");
}

</style>

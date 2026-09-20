<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl49wbrcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl49wbrcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:netlify-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u690nsbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u690nsbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:watch-glyph" /></template>

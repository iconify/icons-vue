<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz6jymbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz6jymbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:refresh-glyph" /></template>

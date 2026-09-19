<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czkzp8abb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="czkzp8abb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:square-half-2" /></template>

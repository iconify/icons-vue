<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6d7x4bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="m6d7x4bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:scissors-open-1" /></template>

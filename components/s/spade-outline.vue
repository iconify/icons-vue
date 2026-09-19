<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa4kkxbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="wa4kkxbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:spade-outline" /></template>

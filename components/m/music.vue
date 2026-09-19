<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym3seqbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ym3seqbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:music" /></template>

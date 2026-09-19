<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz8ezkb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fz8ezkb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:search-tint-bold" /></template>

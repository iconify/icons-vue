<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-e8djbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="g-e8djbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:seven" /></template>

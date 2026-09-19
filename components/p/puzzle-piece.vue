<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whvzwcnoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="whvzwcnoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:puzzle-piece" /></template>

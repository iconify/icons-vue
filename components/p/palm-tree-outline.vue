<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5eihabei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="c5eihabei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:palm-tree-outline" /></template>

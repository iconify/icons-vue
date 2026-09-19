<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8ji8225f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="b8ji8225f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sort-1-bold" /></template>

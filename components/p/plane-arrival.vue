<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2i1ftbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="w2i1ftbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:plane-arrival" /></template>

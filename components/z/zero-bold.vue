<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wob_gub2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="wob_gub2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:zero-bold" /></template>

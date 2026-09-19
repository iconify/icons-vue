<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lovk9xqtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="lovk9xqtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:volume" /></template>

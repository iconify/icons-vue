<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1xb81bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="d1xb81bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:microphone-1-bold" /></template>

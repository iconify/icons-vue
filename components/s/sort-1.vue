<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcf3m5b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xcf3m5b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sort-1" /></template>

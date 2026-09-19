<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v40dffb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="v40dffb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tree-5-outline" /></template>
